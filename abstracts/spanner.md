Spanner is Google's scalable, multi-version, globally-distributed, and
synchronously-replicated database. It is the first system to distribute data at
global scale and support externally-consistent distributed transactions. This
paper describes how Spanner is structured, its feature set, the rationale
underlying various design decisions, and a novel time API that exposes clock
uncertainty. This API and its implementation are critical to supporting external
consistency and a variety of powerful features: non-blocking reads in the past,
lock-free read-only transactions, and atomic schema changes, across all of
Spanner.
