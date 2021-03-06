
.. code::

    $ coverage run --help
    Usage: coverage run [options] <pyfile> [program options]

    Run a Python program, measuring code execution.

    Options:
      -a, --append          Append coverage data to .coverage, otherwise it starts
                            clean each time.
      --branch              Measure branch coverage in addition to statement
                            coverage.
      --concurrency=LIB     Properly measure code using a concurrency library.
                            Valid values are: thread, gevent, greenlet, eventlet,
                            multiprocessing.
      --context=LABEL       The context label to record for this coverage run.
      --include=PAT1,PAT2,...
                            Include only files whose paths match one of these
                            patterns. Accepts shell-style wildcards, which must be
                            quoted.
      -m, --module          <pyfile> is an importable Python module, not a script
                            path, to be run as 'python -m' would run it.
      --omit=PAT1,PAT2,...  Omit files whose paths match one of these patterns.
                            Accepts shell-style wildcards, which must be quoted.
      -L, --pylib           Measure coverage even inside the Python installed
                            library, which isn't done by default.
      -p, --parallel-mode   Append the machine name, process id and random number
                            to the .coverage data file name to simplify collecting
                            data from many processes.
      --source=SRC1,SRC2,...
                            A list of packages or directories of code to be
                            measured.
      --timid               Use a simpler but slower trace method. Try this if you
                            get seemingly impossible results!
      --debug=OPTS          Debug options, separated by commas. [env:
                            COVERAGE_DEBUG]
      -h, --help            Get help on this command.
      --rcfile=RCFILE       Specify configuration file. By default '.coveragerc',
                            'setup.cfg', 'tox.ini', and 'pyproject.toml' are
                            tried. [env: COVERAGE_RCFILE]

