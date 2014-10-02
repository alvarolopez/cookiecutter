======================
cookiecutter-openstack
======================

Cookiecutter template for an OpenStack project. See https://github.com/audreyr/cookiecutter.

* Free software: Apache license
* pbr_: Set up to use Python Build Reasonableness
* hacking_: Enforces the OpenStack Hacking Guidelines
* testrepository_: Runs tests using testrepository
* OpenStack-Infra_: Ready for OpenStack Continuous Integration testing
* Tox_ testing: Setup to easily test for Python 2.6, 2.7, 3.3
* Sphinx_ docs: Documentation ready for generation and publication

Usage
-----

Generate a Python package project::

    cookiecutter https://github.com/alvarolopez/cookiecutter.git

Then, init a git repo for pbr to work before doing anything else::

    cd $repo_name
    git init
    git add .
    git commit -a



.. _pbr: http://docs.openstack.org/developer/pbr
.. _OpenStack-Infra: http://ci.openstack.org
.. _testrepository: https://testrepository.readthedocs.org/
.. _Tox: http://testrun.org/tox/
.. _Sphinx: http://sphinx-doc.org/
.. _hacking: https://git.openstack.org/cgit/openstack-dev/hacking/plain/HACKING.rst
