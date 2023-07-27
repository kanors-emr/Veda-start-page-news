.. Veda news documentation master file, created by
   sphinx-quickstart on Tue Feb 23 11:03:05 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. .. topic::

25 July 2023

`Version 2.016.1.1 <https://github.com/kanors-emr/Veda2.0-Installation>`_ has been released.

   * If you are using version 230 or higher, you can use "Backup State" under Model menu. "Restore State" under higher will Re-synchronize all models and import all VD files that were a part of the old version.
   * CmdF_Top attribute introduced to inject code before the GAMS call in VTRUN.CMD file.
   * Users can specify namespace and model under GAMS Engine settings (Case Manager).
   * We have started developing "Veda Assistant" (VA) functionality that would prove useful for new users as well power users.See "Create Tag" button on Information - Veda and TIMES Parameters.
         * Process/commodity lists are shown on VA - as per the process/commodity filters.

   * Variables $case_name and $vd_file_name introduced in the VTRUN.CMD file, which can help automatic post-processing routines.

`Version History <https://veda-documentation.readthedocs.io/en/latest/pages/version_history.html>`_

.. note::
   * `Veda Online (VO) <https://vedaonline.cloud/>`_ has been launched as a subscription service. New users automatically get fully functional trial license (for 7 days) with 5 hours of solve time in the cloud.
   * Some users have experienced issues under Windows 11. We recommend upgrading to Win 11 after it matures a bit.