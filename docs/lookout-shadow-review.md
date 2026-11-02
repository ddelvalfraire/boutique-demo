# Lookout review smoke test

This temporary document provides a small pull request for exercising Lookout's
review pipeline against the Online Boutique fork.

The change is documentation only. It does not modify application behavior,
dependencies, deployment manifests, or credentials.

The operator will compare the pull request's commit with the recorded Lookout
run, inspect the generated review in the dashboard, and check that shadow mode
does not publish a GitHub review.

This test does not establish private-repository checkout coverage when the
repository is public.
