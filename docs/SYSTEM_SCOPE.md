# DoinBetter ALTA Survey — guarded system scope

This branch begins populating the previously skeletal repository without overstating what exists.

The included ESP32/mesh file is a simulation and design candidate. It is not evidence of field hardware, autonomous surveying, ALTA compliance, accuracy, safety, or production deployment. Its role is to test message shapes and edge-routing ideas while the application contract is built.

The shared trace contract preserves `(x,y,z,w)` samples across voice and future digitizer input. In this lane, `x/y/z` may represent observed geometry and `w` represents measured transit time. Every derived route or survey observation must retain the original sample hash and append a receipt.

Before promotion this repository still needs:

- a licensed source and dependency inventory;
- a coordinate reference system contract;
- ALTA/NSPS requirements mapped to executable acceptance tests;
- calibration, error budgets, and real benchmark datasets;
- privacy, consent, safety, and human-signoff policy;
- hardware-in-the-loop and field validation.
