### Production-ready Node Architecture

> It's made of several small processes that start instantly, maintain no state, and communicate via language-agnostic message bus. Each process logs to stdout and responds to unrecoverable errors by exiting immediately. A load-balancer queues requests, which are served in fixed time by scaling service levels. Configuration controls behavior without any need to deploy new code. Each deploy is archived into a perfect binary copy.
