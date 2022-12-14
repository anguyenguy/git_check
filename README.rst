# LMS2.0

############
edx-platform
############
| |License: AGPL v3| |Status| |Python CI|

.. |License: AGPL v3| image:: https://img.shields.io/badge/License-AGPL_v3-blue.svg
  :target: https://www.gnu.org/licenses/agpl-3.0

.. |Python CI| image:: https://github.com/openedx/edx-platform/actions/workflows/unit-tests.yml/badge.svg
  :target: https://github.com/openedx/edx-platform/actions/workflows/unit-tests.yml

.. |Status| image:: https://img.shields.io/badge/status-maintained-31c653

Purpose
-------
The `Open edX Platform <https://openedx.org>`_ is a service-oriented platform for authoring and
delivering online learning at any scale.  The platform is written in
Python and JavaScript and makes extensive use of the Django
framework. At the highest level, the platform is composed of a
monolith, some independently deployable applications (IDAs), and
micro-frontends (MFEs) based on the ReactJS.

This repository hosts the monolith at the center of the Open edX
platform.  Functionally, the edx-platform repository provides two services:

* CMS (Content Management Service), which powers Open edX Studio, the platform's learning content authoring environment; and
* LMS (Learning Management Service), which delivers learning content.




#################
frontend-app-*
#################

Micro Frontend base plugin for `Tutor <https://docs.tutor.overhang.io>`__
=========================================================================

This plugin makes it possible to easily add micro frontend (MFE) applications on top of an Open edX platform that runs with Tutor. To learn more about MFEs, please check `here <https://github.com/overhangio/tutor-mfe>`__.




#################
indigo
#################

Indigo is an elegant, customizable theme for Open edX. To learn more about Indigo, please check `here <https://github.com/overhangio/tutor-indigo>`__.
