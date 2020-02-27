===========================================
Create Projects and Tasks from Sales Orders
===========================================

When you sell your services, you can choose to automatically have a project/task created, helping
you not to lose track of the work that needs to get done, and to streamline processes between teams.
In addition to that, you will be able to invoice or reinvoice clients according to the exact time
spent on that service.

Product set up
==============

| Under :menuselection:`Sales --> Products --> Products` create a new product or set up an existing
  one. Under *General Information* set the *Product Type* as *Service*. Under the *Sales* tab select
  the *Service Invoicing Policy* and *Service Tracking*.
| If you choose to:

- *Create a task in an existing project*: a task will be added in the first column of the selected
  project.
- *Create a task in sales order’s project*: a new project for each sales order of that service will
  be created based on the template you have chosen.
- *Create a new project but no task*: will only create a new project, for each time that service is
  sold, based on the skeleton of the project template chosen.

.. image:: media/sales_invoicing.png
   :align: center
   :alt: Choose the invoicing options on a product form under the sales tab in Odoo Project

Confirm a quotation and have a project/task created
===================================================

Now, once a *Quotation* is confirmed and transformed into a *Sales Order*, a project or task
will automatically be created.

.. image:: media/confirm_quotation.png
   :align: center
   :alt: Click on confirm in a quotation and have a task or project created for Odoo Project

Access the task generated from Project
======================================

On the *Project* application, your new project and/or task (depending on the previous *Service
Tracking* options chosen), will be shown:

.. image:: media/access_tasks.png
   :align: center
   :height: 250
   :alt: Click on tasks in the dashboard view to access them in Odoo Project

Record the time spent and create an invoice
===========================================

From *Project*, access your task and document the time spent under the *Timesheets* tab.

.. image:: media/record_time.png
   :align: center
   :alt: Access the task and under the tab timesheet record the time spent in Odoo Project

Once the task is complete, click on *Sales Order* and *Create Invoice*.

.. image:: media/sales_order.png
   :align: center
   :alt: Click on sales order in the task once it is complete in Odoo Project

.. tip::
   To invoice only the approved timesheets, go to the *Timesheets* application and under
   :menuselection:`Configuration --> Settings` enable *Approved timesheets only*.

.. seealso::
    - :doc:`../overview/setup`
    - :doc:`../../sales/invoicing/subscriptions`
