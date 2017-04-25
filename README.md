# riemann

This repository contains the Robinhood riemann setup. The riemann
server accepts OpenTSDB events and pushes these events through
configurable consumer streams. About half of these incoming events are
also pushed to a local Elasticsearch instance. All of the events that
result in OK/Non-OK states are pushed to the local Elasticsearch
instance as well.

This setup is further documented
[here](https://medium.com/@aravindg/metrics-riemann-93bb94ed2ff2).
Please read that blog post for the nitty-gritty.
