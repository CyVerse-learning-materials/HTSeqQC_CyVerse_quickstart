.. include:: cyverse_rst_defined_substitutions.txt

|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

**HTSeqQC**
=================

..
    #### Comment: Use short, imperative titles e.g. Upload and share data, uploading and
    sharing data ####

Goal
----

`HTSeqQC <https://github.com/reneshbedre/HTSeqQC>`_ is an automated quality control analysis tool for a single and
paired-end high-throughput sequencing data (HTS) generated from Illumina sequencing platforms.

----

Prerequisites
-------------

Downloads, access, and services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this tutorial you will need access to the following services/software*

..
	#### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Prerequisite
      - Preparation/Notes
      - Link/Download
    * - CyVerse account
      - You will need a CyVerse account to complete this exercise
      - |CyVerse User Portal|
    * - Atmosphere access
      - You must have access to Atmosphere
      - |CyVerse User Portal|
    * - Cyberduck
      - Standalone software for upload/download to Data Store
      - |Download Cyberduck|

Platform(s)
~~~~~~~~~~~

*We will use the following CyVerse platform(s):*

 ..
   #### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Platform
      - Interface
      - Link
      - Platform Documentation
      - Quick Start
    * - Data Store
      - GUI/Command line
      - |Data Store|
      - |Data Store Manual|
      - |Data Store Guide|
    * - Discovery Environment
      - Web/Point-and-click
      - |Discovery Environment|
      - |DE Manual|
      - |Discovery Environment Guide|


Input and example data
~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this tutorial you will need to have the following inputs prepared*

..
	#### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Input File(s)
      - Format
      - Preparation/Notes
      - Example Data
    * - HTS generated Sequence reads
      - `FASTQ <https://en.wikipedia.org/wiki/FASTQ_format>`_
      - Single and Paired-end sequence reads generated from Illumina sequencing platform
      - Test data for this is available in the Discovery Environment in the Data window under Community Data -> iplantcollaborative -> example_data -> htseqqc

----

*Get started:*
-----------------------------------------

.. Tip::

	If you have not already imported your own sequence read files to CyVerse,
	you can follow the instructions for uploading data, for example using
	Cyberduck, in our `Data Store guide <https://cyverse-data-store-guide.readthedocs-hosted.com/en/latest/step1.html>`_



1. Login to the **Discovery Environment (DE)**.

2. Click on the **Apps** in the DE workspace and search for **HTSeqQC**. Click on **HTSeqQC** to open the app.

3. Under “Analysis Name”, you can  use default name or change as appropriate.

4. Under “Input”, provide singe (Input file 1 only) or paired-end (bothInput file 1 and 2) data by clicking "Add" button. Here, you
   can provide single or multiple files for the analysis.

5. Under “Parameter”, select appropriate parameters to run the analysis.

6. Click **Launch Analysis**. You will receive a notification and may close the
   Apps window.

7. Click on **Analyses** from the DE workspace and monitor the status of your
   submitted job (You may have to click refresh to view updated status).

8. In the Analysis console, once your status appears as ‘Completed,’ click
   on the name of your analysis to navigate you to the results.

----


**Fix or improve this documentation**

Search for an answer:
|CyVerse Learning Center| or
|CyVerse Wiki|

----

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`__


.. Comment: Place Images Below This Line
   use :width: to give a desired width for your image
   use :height: to give a desired height for your image
   replace the image name/location and URL if hyperlinked


 .. |Clickable hyperlinked image| image:: ./img/IMAGENAME.png
    :width: 500
    :height: 100
 .. _CyVerse logo: http://learning.cyverse.org/

 .. |Static image| image:: ./img/IMAGENAME.png
    :width: 25
    :height: 25



.. Comment: Place URLS Below This Line

   # Use this example to ensure that links open in new tabs, avoiding
   # forcing users to leave the document, and making it easy to update links
   # In a single place in this document

   .. |Substitution| raw:: html # Place this anywhere in the text you want a hyperlink

      <a href="REPLACE_THIS_WITH_URL" target="blank">Replace_with_text</a>


.. |Github Repo Link|  raw:: html

   <a href="FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX" target="blank">Github Repo Link</a>

.. |Download Cyberduck| raw:: html

   <a href="https://cyberduck.io/" target="blank">Download Cyberduck</a>

.. |DE Application URL|  raw:: html

   <a href="https://de.cyverse.org/de/?type=apps&app-id=9b41c9e4-5031-4a49-b1cb-c471335df16e&system-id=de" target="blank">DE Application URL</a>

.. |Original App Documentation|  raw:: html

   <a href="http://www.drive5.com/muscle/manual/" target="blank">Original App Documentation</a>

.. |Atmosphere Image|  raw:: html

   <a href="https://atmo.cyverse.org/application/images/1384" target="blank">Atmosphere Image</a>
