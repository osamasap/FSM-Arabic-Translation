# FSM Arabic Translation

Arabic translation for the Field Service Management (Beveren FSM) app on
ERPNext / Frappe v16.

**Made for the Egyptian and Arab market.**

Made by Osama (osamasap) together with Muse.

## What it covers

106 Arabic strings for the FSM desk: Service Request, Service Quotation,
Service Order, Service Appointment, Service Report, Service Technician,
Service Type, Service Technician Skill, Service Area, AMC Contract, Repair
Order, Repair Shipment, and the FSM settings and status values.

The React dispatch page (`/schedule`) is a separate frontend and is not
covered by Frappe translation files.

## Install

```bash
bench get-app https://github.com/osamasap/FSM-Arabic-Translation --branch main
bench --site <your-site> install-app fsm_arabic_translation
```

Then set the user's language to Arabic (My Settings → Language) to see the
Arabic interface.

## License

MIT
