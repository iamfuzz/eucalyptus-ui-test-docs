.. Eucalyptus Console Testing Framework Documentation documentation master file, created by
   sphinx-quickstart on Mon Feb  4 11:35:21 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Eucalyptus Console Testing Framework Documentation's documentation!
==============================================================================

Overview
--------

The purpose of this test suite is to automatically verify all basic functionality of the Eucalyptus Console UI works properly across different platforms and browsers before each release.

Most test units are written in Python and use the Standard unittest framework provided there. The tests are executed in the cloud via a Selenium service provided by Sauce Labs.

Some test units are written in shell as they enable certain UI tests to be performed but don't actually use the UI themselves.

All sequentially numbered tests should be run in proper order as some are pre-requisites of the others.  For instance, an instance must be started before it can be terminated.

Tests prefixed with 00 may be run in any order before the sequentially numbered tests have been run (none at this time) and those prefixed with 99 may be run in any order after the rest of the tests have completed.

Individual Test Descriptions
----------------------------

 - `test-01-navBar.py <test-navbar.html>`_
 - `test-02-keyPairs.py <test-keypairs.html>`_
 - `test-03-helpTopics.py <test-helpdocs.html>`_
 - `test-04-fetchCredentials.py <test-fetchcreds.html>`_
 - `test-05-fetchKey.sh <test-fetchkey.html>`_
 - `test-06-modifySecGrp.py <test-modifysecgrp.html>`_
 - `test-07-launchInstance.py <test-launchinstance.html>`_
 - `test-08-createVolume.py <test-createvolume.html>`_
 - `test-09-attachVolume.py <test-attachvolume.html>`_
 - `test-10-testVolume.sh <test-testvolumes.html>`_
 - `test-11-detachVolume.py <test-detachvolume.html>`_
 - `test-12-deleteVolume.py <test-deletevolume.html>`_
 - `test-13-addRemoveSecGrp.py <test-addremsecgrp.html>`_
 - `test-14-rebootInstance.py <test-rebootinstance.html>`_
 - `test-15-terminateInstance.py <test-terminateinstance.html>`_
 - `test-99-verifyCopyrightFooter.py <test-verifycopyfooter.html>`_
