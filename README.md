# Pytest Hook

This is a pre-commit hook to run pytest.

The intended behaviour is that if .py files have been changed in a commit, this hook will run tests that are not marked as slow and refuse the commit if any fail.

If not python files have been altered, this hook should be skipped.
