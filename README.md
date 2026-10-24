# MedCore HMS

MedCore HMS is a hospital management system for the working day of a hospital. Reception, doctors, nurses, the lab, the pharmacy, imaging, the cashier, and administration each have their own desk, and a payment or a result on one desk shows up on the others.

It is installed on the hospital’s own server and sold as a licensed product. A companion online view lets owners and managers see the picture from elsewhere, without moving patient operations off the premises.

## Who it is for

Hospitals that need one system across departments, and owners who need the numbers to match what the cashier actually collected.

## The working day

- Reception registers the patient.
- Doctors, nurses, lab, pharmacy, and imaging do their own work and alert the next desk when the patient is ready.
- The cashier works a real sequence: deposit, bill of discharge, invoice, collect the balance, confirm, then discharge.
- A deposit is its own record. A discharge payment creates a receipt. Marking a screen “paid” is not enough: the money has to appear in Recent Payments and on the patient account.
- Administrators manage staff roles. There are separate roles for the clinical and the money desks, plus a record of who did what.

## Built for a live ward, not a demo

Hospitals cannot reinstall the whole system every time a fee screen is wrong. MedCore ships a numbered patch: stop the service, keep the hospital’s own settings, replace the program, start it again. Schema repairs run on startup so an upgrade does not leave the database half-moved.

The license sits in front of the product. An unlicensed install does not keep operating as if it had been paid for.

## The online view

MedCore HMS Online receives what the hospital system already stores and shows leadership the money, the departments, and staff activity. The clinical system stays on the hospital’s machines.

Inventa Labs keeps the product source private. This page is the public introduction.
