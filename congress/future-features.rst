===============
Future features
===============

Here is a list of features that would be useful in future releases. We have not
prioritized or assigned any of these, so if any of you developers think they
sound fun, let us know and we can explain more.

* Basic Policy language implementation

  * Multi-threaded Datalog implementation

  * Bottom-up datalog evaluation

  * Query optimization

  * Materialized implementation: automated view selection/inlining

* Enhanced Policy language

  * ActiveDirectory facade

  * Syntax improvements (modals like insert/delete)

  * Support for compound objects (safe, stratified recursion)

  * Richer support for describing actions in Enforcement policy

  * Modules

* Policy structure

  * Multi-tenant

  * Multi-stakeholder (tenants, finance, operations, etc.)

* Enforcement

  * Execution of (rich) actions

  * Carve out subpolicies and push to other components, e.g. Neutron

  * Add consultation with Congress to other OS components, e.g. Nova/Neutron

  * Proper remediation enumeration with Classification+Action policies

  * Find ways of automatically choosing the proper remediation strategy (e.g.
    priorities/monotonicity)

  * Give cloud owner way of configuring how proactive/reactive/etc. based on
    information from separate policies.

* Libraries

  * Data source drivers for common OS and non-OS components

  * HIPAA, etc. encoding

  * Ontologies for different sectors, e.g. finance

* Policy Analysis

  * Look for infinite loops through Enforcement policy (using Action policy)

  * Compare Access control policy and Classification policy for redundancy

  * Change impact analysis

* Dashboard

  * IDE for policy (different levels: raw-Datalog, AD, checkbox-based)

  * List violations

  * Explain violations (step-by-step tracing thru policy)

  * Simulate state change and action execution

  * Enumerate remediations for a given violation

* Architecture and API

  * Formalize and implement full introspection and query APIs

  * Distribute across multiple nodes

  * Ensure Congress can use another Congress instance as data

* Authentication and Access Control

  * Add authentication and access controls on API/dashboard

  * When remediating, which user(s) are executing actions? Does Congress need
    admin credentials for all its cloud services or are user credentials part
    of actions? Need proper storage for those credentials. Etc.
