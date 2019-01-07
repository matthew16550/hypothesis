RELEASE_TYPE: patch

This release improves some internal logic about when a test case in Hypothesis's internal representation could lead to a valid test case.
In some circumstances this should lead to a significant speed up during shrinking, but should otherwise have no user visible effect.
