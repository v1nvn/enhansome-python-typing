# Awesome Python Typing [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) [![Gitter](https://img.shields.io/gitter/room/mypy-django/Lobby?color=9cf\&style=flat-square)](https://gitter.im/mypy-django/Lobby?source=title) with stars

Collection of awesome Python types, stubs, plugins, and tools to work with them.

## Contents

* [Static type checkers](#static-type-checkers)
* [Dynamic type checkers](#dynamic-type-checkers)
* [Stub packages](#stub-packages)
* [Additional types](#additional-types)
* [Backports and improvements](#backports-and-improvements)
* [Tools](#tools)
* [Integrations](#integrations)
* [Articles](#articles)
* [Related](#related)

[Full list of typed projects on PyPi](https://pypi.org/search/?q=\&o=\&c=Typing+%3A%3A+Typed) is here.

## Static type checkers

* [mypy](https://github.com/python/mypy) ⭐ 20,219 | 🐛 3,088 | 🌐 Python | 📅 2026-02-18 - Optional static typing (PEP 484).
* [pyright](https://github.com/Microsoft/pyright) ⭐ 15,231 | 🐛 207 | 🌐 Python | 📅 2026-02-17 - Fast type checker meant for large Python source bases. It can run in a “watch” mode and performs fast incremental updates when files are modified.
* [pytype](https://github.com/google/pytype) ⭐ 5,032 | 🐛 5 | 🌐 Python | 📅 2026-01-26 - Tool to check and infer types - without requiring type annotations.
* [basedpyright](https://github.com/detachhead/basedpyright) ⭐ 3,128 | 🐛 615 | 🌐 TypeScript | 📅 2026-02-18 - Pyright fork with improvements to VSCode support and various other fixes.
* [pylyzer](https://github.com/mtshiba/pylyzer/) ⭐ 2,869 | 🐛 29 | 🌐 Rust | 📅 2025-05-10 - A fast static code analyzer & language server for Python, written in Rust.
* [pyanalyze](https://github.com/quora/pyanalyze) ⭐ 378 | 🐛 61 | 🌐 Python | 📅 2026-01-27 - Extensible static analyzer and type checker.
* [basedmypy](https://github.com/KotlinIsland/basedmypy) ⭐ 198 | 🐛 435 | 🌐 Python | 📅 2025-09-10 - Based static typing with baseline functionality.
* [PyCharm](https://www.jetbrains.com/pycharm/) - IDE for Professional Developers.
* [pyre](https://pyre-check.org/) - Performant type-checker.

## Dynamic type checkers

* [pydantic](https://github.com/samuelcolvin/pydantic) ⭐ 26,824 | 🐛 550 | 🌐 Python | 📅 2026-02-17 - Data parsing using Python type hinting. Supports dataclasses.
* [beartype](https://github.com/beartype/beartype) ⭐ 3,336 | 🐛 108 | 🌐 Python | 📅 2026-02-17 - Unbearably fast `O(1)` runtime type-checking in pure Python.
* [typeguard](https://github.com/agronholm/typeguard) ⭐ 1,746 | 🐛 28 | 🌐 Python | 📅 2026-02-15 - Another one runtime type checker.
* [pytypes](https://github.com/Stewori/pytypes) ⭐ 201 | 🐛 39 | 🌐 Python | 📅 2023-04-29 - Provides a rich set of utilities for runtime typechecking.
* [typical](https://github.com/seandstewart/typical/) ⚠️ Archived - Data parsing and automatic type-coercion using type hinting. Supports dataclasses, standard classes, function signatures, and more.
* [strongtyping](https://github.com/FelixTheC/strongtyping) ⭐ 118 | 🐛 3 | 🌐 Python | 📅 2026-01-07 - Decorator which checks whether the function is called with the correct type of parameters.
* [trycast](https://github.com/davidfstr/trycast) ⭐ 87 | 🐛 5 | 🌐 Python | 📅 2025-12-10 - Parse JSON-like values whose shape is defined by typed dictionaries (TypedDicts) and other standard Python type hints.
* [typedpy](https://github.com/loyada/typedpy) ⭐ 17 | 🐛 3 | 🌐 Python | 📅 2024-09-24 - Type-safe, strict Python. Works well with standard Python.

## Stub packages

* [boto3-stubs](https://vemel.github.io/boto3_stubs_docs/) - Stubs for [boto3](https://github.com/boto/boto3) ⭐ 9,691 | 🐛 175 | 🌐 Python | 📅 2026-02-17.
* [typeshed](https://github.com/python/typeshed) ⭐ 5,003 | 🐛 352 | 🌐 Python | 📅 2026-02-16 - Collection of library stubs, with static types.
* [django-stubs](https://github.com/typeddjango/django-stubs) ⭐ 1,891 | 🐛 232 | 🌐 Python | 📅 2026-02-17 - Stubs for [Django](https://github.com/django/django) ⭐ 86,787 | 🐛 415 | 🌐 Python | 📅 2026-02-16.
* [asgiref](https://github.com/django/asgiref) ⭐ 1,616 | 🐛 67 | 🌐 Python | 📅 2026-02-03 - ASGI specification, provides [asgiref.typing](https://github.com/django/asgiref/blob/main/asgiref/typing.py) ⭐ 1,616 | 🐛 67 | 🌐 Python | 📅 2026-02-03 module with type annotations for ASGI servers.
* [torchtyping](https://github.com/patrick-kidger/torchtyping) ⭐ 1,471 | 🐛 16 | 🌐 Python | 📅 2025-05-02 - Enhanced type annotations for [PyTorch](https://pytorch.org/).
* [types-aiobotocore](https://vemel.github.io/types_aiobotocore_docs/) - Stubs for [aiobotocore](https://github.com/aio-libs/aiobotocore) ⭐ 1,384 | 🐛 16 | 🌐 Python | 📅 2026-02-16.
* [sqlalchemy-stubs](https://github.com/dropbox/sqlalchemy-stubs) ⭐ 583 | 🐛 87 | 🌐 Python | 📅 2024-06-10 - Stubs for [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy) ⭐ 11,518 | 🐛 209 | 🌐 Python | 📅 2026-02-16.
* [djangorestframework-stubs](https://github.com/typeddjango/djangorestframework-stubs) ⭐ 529 | 🐛 61 | 🌐 Python | 📅 2026-02-17 - Stubs for [DRF](https://github.com/encode/django-rest-framework) ⭐ 29,876 | 🐛 88 | 🌐 Python | 📅 2026-02-17.
* [celery-types](https://github.com/sbdchd/celery-types) ⭐ 139 | 🐛 7 | 🌐 Python | 📅 2026-01-12 - Type stubs for [Celery](https://github.com/celery/celery) ⭐ 28,029 | 🐛 771 | 🌐 Python | 📅 2026-02-17 and its related packages [django-celery-results](https://github.com/celery/django-celery-results) ⭐ 773 | 🐛 59 | 🌐 Python | 📅 2025-11-24, [ampq](https://github.com/celery/py-amqp) ⭐ 314 | 🐛 39 | 🌐 Python | 📅 2026-02-05, [kombu](https://github.com/celery/kombu) ⭐ 3,103 | 🐛 236 | 🌐 Python | 📅 2026-02-16, [billiard](https://github.com/celery/billiard) ⭐ 430 | 🐛 85 | 🌐 Python | 📅 2026-02-05, [vine](https://github.com/celery/vine) ⭐ 128 | 🐛 7 | 🌐 Python | 📅 2026-01-17 and [ephem](https://github.com/brandon-rhodes/pyephem) ⭐ 881 | 🐛 4 | 🌐 C | 📅 2025-07-01.
* [botostubs](https://github.com/jeshan/botostubs) ⭐ 94 | 🐛 11 | 🌐 Python | 📅 2023-02-07 - Gives you code assistance for any boto3 API in any IDE.
* [scipy-stubs](https://github.com/jorenham/scipy-stubs) ⭐ 83 | 🐛 19 | 🌐 Python | 📅 2026-02-16 - Stubs for [SciPy](https://github.com/scipy/scipy) ⭐ 14,461 | 🐛 1,775 | 🌐 Python | 📅 2026-02-17.
* [PyQt5-stubs](https://github.com/stlehmann/PyQt5-stubs) ⭐ 71 | 🐛 14 | 🌐 Python | 📅 2023-07-23 - Stubs for [PyQt5](https://www.riverbankcomputing.com/software/pyqt/intro).
* [lxml-stubs](https://github.com/lxml/lxml-stubs) ⭐ 51 | 🐛 22 | 🌐 Python | 📅 2025-11-21 - Stubs for [lxml](https://lxml.de).
* [grpc-stubs](https://github.com/shabbyrobe/grpc-stubs) ⚠️ Archived - Stubs for [grpc](https://github.com/grpc/grpc) ⭐ 44,371 | 🐛 1,181 | 🌐 C++ | 📅 2026-02-18.
* [pythonista-stubs](https://github.com/hbmartin/pythonista-stubs) ⭐ 21 | 🐛 6 | 🌐 Python | 📅 2025-08-13 - Stubs for [Pythonista](http://omz-software.com/pythonista/docs/ios/).
* [python-phonenumbers-stubs](https://github.com/AA-Turner/python-phonenumbers-stubs) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-09-01 - Stubs for [phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) ⭐ 3,708 | 🐛 12 | 🌐 Python | 📅 2026-02-13.
* [sqlalchemy2-stubs](https://docs.sqlalchemy.org/en/14/orm/extensions/mypy.html) - Official stubs and mypy plugin for [SQLAlchemy](https://www.sqlalchemy.org).

## Additional types

* [returns](https://github.com/dry-python/returns) ⭐ 4,222 | 🐛 80 | 🌐 Python | 📅 2026-02-16 - Make your functions return something meaningful, typed, and safe.
* [phantom-types](https://github.com/antonagestam/phantom-types) ⭐ 233 | 🐛 18 | 🌐 Python | 📅 2026-01-01 - Phantom types.
* [useful-types](https://github.com/hauntsaninja/useful_types) ⭐ 148 | 🐛 14 | 🌐 Python | 📅 2026-01-05 - Collection of useful protocols and type aliases.
* [option](https://github.com/MaT1g3R/option) ⭐ 100 | 🐛 8 | 🌐 Python | 📅 2024-01-01 - Rust like Option and Result types.
* [meiga](https://github.com/alice-biometrics/meiga) ⭐ 81 | 🐛 1 | 🌐 Python | 📅 2024-10-22 - Simple, typed and monad-based Result type.
* [optype](https://github.com/jorenham/optype) ⭐ 75 | 🐛 11 | 🌐 Python | 📅 2026-02-16 - Opinionated `collections.abc` and `operators` alternative: Flexible single-method protocols and typed operators with predictable names.
* [safetywrap](https://github.com/mplanchard/safetywrap) ⭐ 46 | 🐛 0 | 🌐 Python | 📅 2020-09-23 - Fully typesafe, Rust-like Result and Option types.
* [typet](https://github.com/contains-io/typet) ⚠️ Archived - Length-bounded types, dynamic object validation.

## Backports and improvements

* [typing-extensions](https://github.com/python/typing_extensions) ⭐ 550 | 🐛 26 | 🌐 Python | 📅 2026-02-09 - Backported and experimental type hints.
* [future-typing](https://github.com/PrettyWood/future-typing) ⭐ 19 | 🐛 5 | 🌐 Python | 📅 2021-05-14 - Backport for type hinting generics in standard collections and union types as `X | Y`.
* [typing-utils](https://github.com/bojiang/typing_utils) ⭐ 12 | 🐛 2 | 🌐 Python | 📅 2022-11-09 - Backport 3.8+ runtime typing utils(for eg: get\_origin) & add issubtype & more.

## Tools

### Linters

* [Ruff](https://github.com/astral-sh/ruff/) ⭐ 45,816 | 🐛 1,902 | 🌐 Rust | 📅 2026-02-18 - Extremely fast linter which supports lint rules from many other lint tools, such as flake8.
* [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) ⭐ 2,822 | 🐛 26 | 🌐 Python | 📅 2026-02-17 - The strictest and most opinionated Python linter ever.
* [flake8-annotations](https://github.com/sco1/flake8-annotations) ⭐ 163 | 🐛 0 | 🌐 Python | 📅 2026-01-07 - Plugin for flake8 to check for presence of type annotations in function definitions.
* [flake8-type-checking](https://github.com/snok/flake8-type-checking) ⭐ 129 | 🐛 4 | 🌐 Python | 📅 2026-01-09 - Plugin to help you guard any type-annotation-only import correctly.
* [flake8-typing-only-imports](https://github.com/sondrelg/flake8-typing-only-imports) ⭐ 129 | 🐛 4 | 🌐 Python | 📅 2026-01-09 - flake8 plugin that helps identify which imports to put into type-checking blocks, and how to adjust your type annotations once imports are moved.
* [flake8-pyi](https://github.com/ambv/flake8-pyi) ⭐ 80 | 🐛 19 | 🌐 Python | 📅 2026-01-08 - Plugin for Flake8 that provides specializations for type hinting stub files.
* [flake8-annotations-complexity](https://github.com/best-doctor/flake8-annotations-complexity) ⭐ 51 | 🐛 4 | 🌐 Python | 📅 2025-03-04 - Plugin for flake8 to validate annotations complexity.
* [flake8-typing-imports](https://github.com/asottile/flake8-typing-imports) ⭐ 51 | 🐛 0 | 🌐 Python | 📅 2025-12-22 - Plugin which checks that typing imports are properly guarded.
* [flake8-type-ignore](https://gitlab.com/jonafato/flake8-type-ignore/) - flake8 plugin to disallow type: ignore comments in your typed Python code.

### Testing

* [pytest-mypy](https://github.com/dbader/pytest-mypy) ⭐ 257 | 🐛 8 | 🌐 Python | 📅 2025-04-02 - Mypy static type checker plugin for Pytest.
* [pytest-mypy-plugins](https://github.com/typeddjango/pytest-mypy-plugins) ⭐ 123 | 🐛 28 | 🌐 Python | 📅 2026-02-16 - Pytest plugin for testing mypy types, stubs, and plugins.
* [pytest-mypy-testing](https://github.com/davidfritzsche/pytest-mypy-testing) ⭐ 34 | 🐛 9 | 🌐 Python | 📅 2026-01-26 - Pytest plugin to test mypy static type analysis.
* [mypy-test](https://github.com/orsinium-labs/mypy-test) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-10-24 - Test mypy plugins, stubs, custom types.

### Working with types

* [mypyc](https://github.com/python/mypy/tree/master/mypyc) ⭐ 20,219 | 🐛 3,088 | 🌐 Python | 📅 2026-02-18 - Compiles mypy-annotated, statically typed Python modules into CPython C extensions.
* [merge-pyi](https://github.com/google/pytype/tree/master/pytype/tools/merge_pyi) ⭐ 5,032 | 🐛 5 | 🌐 Python | 📅 2026-01-26 - Part of pytype toolchain, applies stub files onto source code.
* [mypy-protobuf](https://github.com/dropbox/mypy-protobuf) ⭐ 696 | 🐛 30 | 🌐 Python | 📅 2026-02-16 - Tool to generate mypy stubs from protobufs.
* [typing-inspect](https://github.com/ilevkivskyi/typing_inspect) ⭐ 376 | 🐛 24 | 🌐 Python | 📅 2026-01-18 - The typing\_inspect module defines experimental API for runtime inspection of types defined in the `typing` module.
* [com2ann](https://github.com/ilevkivskyi/com2ann) ⭐ 156 | 🐛 10 | 🌐 Python | 📅 2025-06-02 - Tool for translation of type comments to type annotations.
* [retype](https://github.com/ambv/retype) ⭐ 146 | 🐛 1 | 🌐 Python | 📅 2022-08-14 - Another tool to apply stubs to code.
* [typesplainer](https://github.com/wasi-master/typesplainer) ⭐ 83 | 🐛 1 | 🌐 Python | 📅 2023-07-19 - A Python type explainer.
* [mypy-baseline](https://github.com/orsinium-labs/mypy-baseline) ⭐ 77 | 🐛 1 | 🌐 Python | 📅 2025-05-30 - Integrate mypy with existing codebase. A CLI tool that filters out existing type errors and reports only new ones.
* [typeforce](https://github.com/orsinium-labs/typeforce) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2022-09-30 - CLI tool that enriches your Python environment with type annotations, empowering mypy.
* [mypy-silent](https://github.com/whtsky/mypy-silent/) ⭐ 18 | 🐛 13 | 🌐 Python | 📅 2026-02-16 - Silence mypy by adding or removing code comments.
* [typing-json](https://pypi.org/project/typing-json/) - Lib for working with typed objects and JSON.

### Helper tools to add annotations to existing code

* [pyre infer](https://github.com/facebook/pyre-check) ⭐ 7,145 | 🐛 154 | 🌐 OCaml | 📅 2026-02-17 - Pyre has a powerful feature for migrating codebases to a typed format. The [infer](https://pyre-check.org/docs/pysa-coverage/) command-line option ingests a file or directory, makes educated guesses about the types used, and applies the annotations to the files.
* [pytype annotate-ast](https://github.com/google/pytype/tree/master/pytype/tools/annotate_ast) ⭐ 5,032 | 🐛 5 | 🌐 Python | 📅 2026-01-26 - A work-in-progress tool to annotate the nodes of an AST with their Python types.
* [monkeytype](https://github.com/instagram/MonkeyType) ⭐ 4,994 | 🐛 68 | 🌐 Python | 📅 2026-02-11 - Collects runtime types of function arguments and return values, and can automatically generate stub files or even add draft type annotations directly to your code based on the types collected at runtime.
* [pyannotate](https://github.com/dropbox/pyannotate) ⭐ 1,449 | 🐛 36 | 🌐 Python | 📅 2022-07-03 - Insert annotations into your source code based on call arguments and return types observed at runtime.
* [RightTyper](https://github.com/RightTyper/RightTyper) ⭐ 350 | 🐛 3 | 🌐 Python | 📅 2026-02-06 - A tool that generates types for your function arguments and return values. RightTyper lets your code run at nearly full speed with almost no memory overhead.
* [autotyping](https://github.com/JelleZijlstra/autotyping) ⭐ 282 | 🐛 8 | 🌐 Python | 📅 2025-09-19 - Automatically add simple return type annotations for functions (bool, None, Optional).
* [pytest-annotate](https://github.com/kensho-technologies/pytest-annotate) ⭐ 113 | 🐛 0 | 🌐 Python | 📅 2022-06-07 - Pyannotate plugin for pytest.
* [no\_implicit\_optional](https://github.com/hauntsaninja/no_implicit_optional) ⭐ 105 | 🐛 2 | 🌐 Python | 📅 2023-11-25 - A codemod to make your implicit optional type hints [PEP 484](https://peps.python.org/pep-0484/#union-types) compliant.
* [infer-types](https://github.com/orsinium-labs/infer-types) ⭐ 98 | 🐛 0 | 🌐 Python | 📅 2023-03-17 - CLI tool to automatically infer and add type annotations into Python code.
* [type4py](https://github.com/saltudelft/type4py) ⭐ 65 | 🐛 6 | 🌐 Python | 📅 2023-09-06 - Deep Similarity Learning-Based Type Inference.
* [typilus](https://github.com/typilus/typilus) ⭐ 62 | 🐛 6 | 🌐 Python | 📅 2023-02-08 - A deep learning algorithm for predicting types in Python. Also available as a [GitHub action](https://github.com/typilus/typilus-action) ⭐ 42 | 🐛 12 | 🌐 Python | 📅 2023-03-23
* [jsonschema-gentypes](https://github.com/camptocamp/jsonschema-gentypes) ⭐ 48 | 🐛 19 | 🌐 Python | 📅 2026-02-11 - Generate Python types based on TypedDict from a JSON Schema.
* [pytest-monkeytype](https://github.com/mariusvniekerk/pytest-monkeytype) ⭐ 46 | 🐛 1 | 🌐 Python | 📅 2020-07-29 - MonkeyType plugin for pytest.
* [auto-optional](https://github.com/Luttik/auto-optional) ⭐ 18 | 🐛 5 | 🌐 Python | 📅 2025-07-02 - Makes typed arguments Optional when the default argument is `None`.
* [PyTypes](https://github.com/pvs-hd-tea/PyTypes) ⭐ 11 | 🐛 9 | 🌐 Python | 📅 2022-08-29 - Infer Types by Python Tracing.

### Mypy plugins

* [mypy/plugins](https://github.com/python/mypy/tree/master/mypy/plugins) ⭐ 20,219 | 🐛 3,088 | 🌐 Python | 📅 2026-02-18 - Plugins already integrated into mypy.
* [mypy-zope](https://github.com/Shoobx/mypy-zope) ⭐ 40 | 🐛 20 | 🌐 Python | 📅 2025-12-01 - Plugin for [zope.interface](https://zopeinterface.readthedocs.io/en/latest/) support.
* [kubernetes-typed](https://github.com/gordonbondon/kubernetes-typed) ⭐ 27 | 🐛 3 | 🌐 Python | 📅 2024-09-08 - Plugin for Kubernetes [CRD](https://kubernetes.io/docs/tasks/extend-kubernetes/custom-resources/custom-resource-definitions/) type checking.
* [loguru-mypy](https://github.com/kornicameister/loguru-mypy) ⭐ 22 | 🐛 16 | 🌐 Python | 📅 2024-05-01 - Plugin for [loguru](https://github.com/Delgan/loguru) ⭐ 23,596 | 🐛 250 | 🌐 Python | 📅 2026-01-15 support.
* [pynamodb-mypy](https://github.com/pynamodb/pynamodb-mypy) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2022-10-21 - Plugin for [PynamoDB](https://github.com/pynamodb/PynamoDB) ⭐ 2,647 | 🐛 317 | 🌐 Python | 📅 2026-01-06 support.
* [NumPy](https://numpy.org/devdocs/reference/typing.html) - Plugin for [NumPy](https://numpy.org) support.
* [pydantic](https://docs.pydantic.dev/latest/integrations/mypy/) - Plugin for additional [Pydantic](https://docs.pydantic.dev/latest/) support.

## Integrations

* [pylance](https://github.com/microsoft/pylance-release) ⭐ 1,996 | 🐛 425 | 🌐 Python | 📅 2026-02-14 - PyRight integration for VSCode.
* [nbQA](https://github.com/nbQA-dev/nbQA) ⭐ 1,189 | 🐛 19 | 🌐 Python | 📅 2026-02-03 - Run type checkers (e.g. Mypy) on Jupyter Notebooks.
* [mypy-pycharm-plugin](https://github.com/dropbox/mypy-PyCharm-plugin) ⭐ 320 | 🐛 19 | 🌐 Java | 📅 2021-06-23 - Mypy integration for PyCharm.
* [vim-mypy](https://github.com/Integralist/vim-mypy) ⭐ 101 | 🐛 2 | 🌐 VimL | 📅 2019-10-08 - Mypy integration for Vim.
* [mypy-playground](https://github.com/ymyzk/mypy-playground) ⭐ 76 | 🐛 45 | 🌐 Python | 📅 2026-02-17 - Online playground for mypy.
* [emacs-flycheck-mypy](https://github.com/lbolla/emacs-flycheck-mypy) ⭐ 38 | 🐛 2 | 🌐 Emacs Lisp | 📅 2020-03-30 - Mypy integration for Emacs.

## Articles

### PEPs

* [PEP-3107](https://www.python.org/dev/peps/pep-3107) - Function Annotations.
* [PEP-482](https://www.python.org/dev/peps/pep-0482/) - Literature Overview for Type Hints.
* [PEP-483](https://www.python.org/dev/peps/pep-0483/) - The Theory of Type Hints.
* [PEP-484](https://www.python.org/dev/peps/pep-0484/) - Type Hints.
* [PEP-526](https://www.python.org/dev/peps/pep-0526/) - Syntax for Variable Annotations.
* [PEP-544](https://www.python.org/dev/peps/pep-0544/) - Protocols: Structural subtyping (static duck typing).
* [PEP-557](https://www.python.org/dev/peps/pep-0557/) - Data Classes.
* [PEP-560](https://www.python.org/dev/peps/pep-0560/) - Core support for typing module and generic types.
* [PEP-561](https://www.python.org/dev/peps/pep-0561/) - Distributing and Packaging Type Information.
* [PEP-563](https://www.python.org/dev/peps/pep-0563/) - Postponed Evaluation of Annotations.
* [PEP-585](https://www.python.org/dev/peps/pep-0585/) - Type Hinting Generics In Standard Collections.
* [PEP-586](https://www.python.org/dev/peps/pep-0586/) - Literal Types.
* [PEP-589](https://www.python.org/dev/peps/pep-0589/) - TypedDict: Type Hints for Dictionaries with a Fixed Set of Keys.
* [PEP-591](https://www.python.org/dev/peps/pep-0591/) - Adding a final qualifier to typing.
* [PEP-593](https://www.python.org/dev/peps/pep-0593/) - Flexible function and variable annotations.
* [PEP-604](https://www.python.org/dev/peps/pep-0604/) - Complementary syntax for Union\[].
* [PEP-612](https://www.python.org/dev/peps/pep-0612/) - Parameter Specification Variables.
* [PEP-613](https://www.python.org/dev/peps/pep-0613/) - Explicit Type Aliases.

### Third-party articles

* [1-minute guide to real constants in Python](https://sobolevn.me/2018/07/real-python-contants) - Full tutorial about `Final` constants and inheritance.
* [Simple dependent types in Python](https://sobolevn.me/2019/01/simple-dependent-types-in-python) - Full tutorial about `Literal` types.
* [Testing mypy stubs, plugins, and types](https://sobolevn.me/2019/08/testing-mypy-types) - Full tutorial about testing mypy types.
* [Our journey to type checking 4 million lines of Python](https://dropbox.tech/application/our-journey-to-type-checking-4-million-lines-of-python) - Dropbox has been one of the first companies to adopt Python static type checking at this scale.
* [PyTest MonkeyType Introduction](https://dev.to/ldrscke/type-annotate-an-existing-python-django-codebase-with-monkeytype-254i) - Type Annotate an existing Python Django Codebase with MonkeyType.
* [The state of type hints in Python](https://bernat.tech/posts/the-state-of-type-hints-in-python/) - As of May 2018.
* [Type hints cheat sheet](https://mypy.readthedocs.io/en/latest/cheat_sheet_py3.html) - Cheat sheet on writing type annotations by MyPy team.
* [Typechecking Django and DRF](https://sobolevn.me/2019/08/typechecking-django-and-drf) - Full tutorial about type-checking Django.
* [Type Check Your Django Application](https://kracekumar.com/post/type_check_your_django_app/) - An article based on two recent talks on adding type checks to Django.
* [typing](https://docs.python.org/3/library/typing.html) - Official Python documentation for `typing` module.
* [Python-typing-koans](https://github.com/kracekumar/python-typing-koans/) ⭐ 119 | 🐛 7 | 🌐 Python | 📅 2021-12-18 - A set of examples to learn optional static typing in Python.
* [Python Type Checking (Guide)](https://realpython.com/python-type-checking/) - In this guide, you will get a look into Python type checking.
* [Adding type hints to urllib3](https://sethmlarson.dev/blog/2021-10-18/tests-arent-enough-case-study-after-adding-types-to-urllib3) - Tests are not enough: Case study adding type hints to urllib3.
* [Adam Johnsons Blog](https://adamj.eu/tech/tag/mypy/) - Adam Johnson blogs about typing practices.
* [ParamSpec Guide](https://sobolevn.me/2021/12/paramspec-guide) - Newly released feature in `PEP612` allows you do a lot of advanced typing things with functions and their signatures.
* [Static Typing Python Decorators](https://rednafi.github.io/reflections/static-typing-python-decorators.html) - Accurately static typing decorators in Python is an icky business. The wrapper function obfuscates type information required to statically determine the types of the parameters and the return values of the wrapped function.

## Related

* [awesome-python](https://github.com/vinta/awesome-python) ⭐ 283,305 | 🐛 16 | 🌐 Python | 📅 2026-02-17 - Curated list of awesome Python frameworks, libraries, software and resources.
* [python-typecheckers](https://github.com/ethanhs/python-typecheckers) ⭐ 71 | 🐛 2 | 📅 2025-12-01 - List of Python type checkers: static and runtime.
