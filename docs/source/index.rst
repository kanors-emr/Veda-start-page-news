.. Veda news documentation master file, created by
   sphinx-quickstart on Tue Feb 23 11:03:05 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. .. topic::

07 February 2024

`Version 3.0.5.0 <https://github.com/kanors-emr/Veda2.0-Installation>`_ has been released. This fixes a bug related to DINS tables in BY/SubRES Trans files that was introduced in version 3.0.3.

.. caution::
   This is a major release. Your license should have maintenance covered beyond 28 November 2023 to be able to use this version (and above)


* Excel file reading and writing is now done using a third-party library `ASPOSE <https://products.aspose.com/cells/>`_. This makes the synchronization process much faster, and also more robust, because we no loger rely on the local Excel installation.
* We have started developing "Veda Assistant" (VA) functionality that would prove useful for new users as well power users.See "Create Tag" button on Information - Veda and TIMES Parameters.

   * Process/commodity lists are shown on VA - as per the process/commodity filters.

`Version History <https://veda-documentation.readthedocs.io/en/latest/pages/version_history.html>`_

.. note::
   * `Veda Online (VO) <https://vedaonline.cloud/>`_ has been launched as a subscription service. New users automatically get fully functional trial license (for 7 days) with 5 hours of solve time in the cloud.
   * Veda works well under Windows 11.