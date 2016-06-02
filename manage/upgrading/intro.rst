============
Introduction
============

.. admonition:: Description

   What we are talking about.

.. contents:: :local:


What does it mean to upgrade Plone?
===================================

This document covers the procedures and issues involved in upgrading an existing Plone installation. This involves both the upgrading of the program set, and migration of the site itself.

Generally, you will often see the word *migration* used as the word we use to describe the process of getting your Plone site from one version of a given component to a newer version. For most people, this means upgrading Plone to a newer release, for example from 4.3.x to 5.0.x.

Migration is necessary because the internals of Plone sometimes change to support new functionality. When that's the case, the content which is stored in your Plone instance may not match what the new version of the software expects.
Plone has a builtin tool that migrates existing content to the new structure.

This guide describes migration in Plone, specifically how you upgrade between different versions.

Before migrating you should read this entire document to understand the potential impact migrating will have on your Plone site.

It is also wise to have read the :doc:`troubleshooting <troubleshooting>` section, just in case you may need to employ one of the techniques there.

The guide applies to all contemporary versions of Plone.
For unsupported versions from the year 2009 and before, see older versions of this documentation.


A note about version numbering and terminology
==============================================

Since the Plone 2.5 release, Plone has a policy that increases the version number to a .0 on every major release. This means that when we say a *major release*, we are referring to a x.0 release, whereas a minor release has the version numbering 4.3.7 or 5.1.0

In addition to the general procedure there are :doc:`version-specific migration guides </manage/upgrading/version_specific_migration/index>`. These guides contain more specific instructions and valuable information that has been collected from real-life migration cases.

