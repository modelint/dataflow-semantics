# Welcome to the Data Flow Semantics 

Here we model the semantics and execution rules of simple data flow diagrams using Shlaer-Mellor Executable UML

Remember data flow diagrams from the '80s? That's okay, not many people do.
If you are familiar with UML activity diagrams these are a weird fusion of flowcharts from the 60-70's and data flow diagrams from the 70-80's.
Not familiar with those either? Yeah, nobody much cares about those either, yawn...

**BUT** data flow diagrams on their own are simple and powerful.

We use them for Executable UML model actions such as: filter instances, compute value, test value/if-then, send signal, traverse relationship, invoke class method, and so forth. By separating out this domain, however, you could configure your data flow graphs for any kinds of actions.

What we like about data flow diagrams is that they provide a way to specify the execution order of both parallel and sequenced actions.

This is important if you are building platform independent models like we do in the Shlaer-Mellor Executable UML community.
We don't tell the programmer (or model compiler) to execute actions in any particular order UNLESS that order is essential on all platforms.

This work was motivated by the sm-metamodel work. In the process of building the Shlaer-Mellor metamodel it became obvious that data flow diagrams and the related semantics were an entirely separate subject subject matter. Therefore, it is it's own distinct model domain.

There's no code in this repository. The models are all Shlaer-Mellor Executable UML. We use the Flatland tool to draw our models.

Everything else is in the [wiki](https://github.com/modelint/dataflow-semantics/wiki).

There is also a [discussion group](https://github.com/modelint/dataflow-semantics/discussions) if you have questions or comments.
