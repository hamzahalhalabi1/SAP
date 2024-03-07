# SAP
Assembly line using SAP S/4HANA

Project Description: SAP Production and Planning

Objective:
The project aims to streamline production and planning processes within the SAP system. Utilizing your user ID and password, the tasks involve defining products, creating bills of materials (BOMs), establishing routings, forecasting, running Material Requirements Planning (MRP), and managing production orders.

Tasks:

Product Definition (MM01):

Define a finished good named "Bike."
Set language maintenance for Turkish and English.
Assign storage location Z001.
Planning strategy group: 40 (MİP3 screen).
Set a safety stock of 10 for finished goods.
Define three semi-finished goods (Frame assembly, Wheel, and Frame).
Bill of Materials (CS01):

Create BOMs for Bike, Frame assembly, Wheel, and Frame.
Utilize existing SAP Material Numbers and Material Definitions for raw materials.
BOM Correction (CS02):

Identify and correct BOM mistake related to Frame assembly.
Routing Definition (CA01):

Define routing for Bike, Frame assembly, Wheel, and Frame using workcenters Z_PKT and Z_MNT.
Specify setup and operation times for each workcenter.
Choose control key PP03 for both workcenters.
BOM-Routing Matching (C223):

Ensure alignment between defined BOMs and their respective routings.
Forecasting (MD61):

Define a forecast for 100 units of the Bike for May 2023.
MRP Run (MD02):

Execute MRP for the Bike.
Verify the creation of planned orders for the Bike and semi-finished goods using MD04.
Set MRP parameters as NETCH-1-3-1-3-1.
Planned Order Conversion (MD04):

Convert planned order releases of the Bike and semi-finished goods to production orders.
Production Order Completion (CO11N):

Assume completion of production for bikes and semi-finished goods.
Use CO11N to complete production orders, starting from semi-finished goods.
Stock Verification (MMBE, MB52):

Verify the stock of bikes in storage location Z001.
Check stock using MMBE and MB52.
Export the table from MB52 to an Excel file for record-keeping.
Note: Adhere to SAP best practices and document all changes made in the SAP system for future reference.
