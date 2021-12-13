Alamvic
#######


.. toctree::
    :hidden:

    projects
    positions
    readings/index
    Pharo <https://pharo.org>
    RMoD <https://rmod.gitlabpages.inria.fr/website/>
    Inria <https://inria.fr>

Language Virtual Machines (VMs) are pervasive in every laptop, server and smartphone. Industry-level VMs use highly-engineered optimisation techniques, often handcrafted by experts, difficult to reproduce, replicate and change. Such optimisation techniques target mostly speed improvements, and are incompatible with constraints such as space and energy efficiency important in the fields of IoT or robotics.

In AlaMVic we propose to approach VM construction using a holistic generative approach, in contrast with existing approaches that focus on speed and single VM
components such as the JIT compiler. We explore how to transform handcrafted optimisations into generation heuristics. We envisage to create a VM distillation toolchain in the form of open source software where a VM is generated from a high-level language specification plus optimisation hints.

AlaMVic is an exploratory action project funded since the end of 2021 by Inria (https://inria.fr), within the RMoD team (https://rmod.gitlabpages.inria.fr/website/).


News
=====

.. important::
  We will present in MPLR'21 our work around profiling code caches and Virtual Machine unit testing!
  https://wwuindico.uni-muenster.de/event/449/program