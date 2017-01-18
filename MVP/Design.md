## MVP: Design decisions
Decisions that primarily make sense for MVP, and should be re-evaluated after MVP.

- Use the logs host to serve both job output logs and also internal service logs (nodepool/zuul).
  Eventually these should be stored on and served by different hosts.
