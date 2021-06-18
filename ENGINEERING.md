# Software engineering principles

## Observability (o11y)

Software observability is the ability to answer unknown-unknowns, or to derive understanding about systems too complex for humans to fully understand, through making dynamic inquiries and empirical observations about that system's behavior/state.

As far as I know, this term was pioneered by [Honeycomb.io](https://honeycomb.io), which is also my former employer and my absolute favorite tool for asking complex questions of complex software systems. It achieves this through high-cardinality query performance over extremely large bodies of structured timestamped log data and discoverable persistent queries.

Observability is extremely distinct from _monitoring_, in which complex bodies of data are (lossily) pre-aggregated to answer known-unknowns.

## Systematic debugging

- ["Computers Can Be Understood" (Nelson Elhage)](https://blog.nelhage.com/post/computers-can-be-understood/)

## Design philosophy

[Small Sharp Tools | Brandur](https://brandur.org/small-sharp-tools)
> the idea of building minimalist, composable programs that worked in concert to a degree of effectiveness that was more than the sum of their parts

[Local-first software | Ink & Switch](https://www.inkandswitch.com/local-first.html)
