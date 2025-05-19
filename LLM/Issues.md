This memory transfer is an exception to the usual process, because the memory tables are in the middle of a revision to suit the current system document. Instead of proceeding with planning, we want to continue that migration. Any tables with the "Legacy-" prefix are remnants of the old schema, they're only there for reference. You should expect some tables to be missing from the new schema.

To start with, after you ingest the memory transfer, please perform an analysis on the internal consistency of the system, and report:
- any consistency issues
- what areas of the system might be incomplete
- what tables you expected to see that are not present
- what rows you expected to be complete but aren't.
- what rows you expected to see that are not present.

* need better/more capability goal for comprehension (comprehensible input expansion), without being overly quantitative
* What do we do about the "targets"?
* missing log tables
* priority tiers not assigned to activities
* 