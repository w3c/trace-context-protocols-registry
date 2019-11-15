## Purpose

Trace context [[TRACE-CONTEXT]] consists of properties crucial for event
correlation, used to monitor the health and reliability of a distributed
application. The [[TRACE-CONTEXT]] specification defines the binding of the
distributed trace context to `traceparent` and
`tracestate` <a
data-cite="TRACE-CONTEXT#trace-context-http-headers-format">HTTP headers</a>.

This registry is intended to provide a central location for enumerating
identified formats of trace context [[TRACE-CONTEXT]] serialization and
deserialization for protocols. By utilizing a common registry, it is possible to
provide common trace context serialization and deserialization for other
protocols.
