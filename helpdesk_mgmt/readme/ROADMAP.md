- Add a tour feature similar to what the `project` module defines to
  discover projects / tasks.
- Update portal tests defined in `tests/test_portal.py` to rely on tour
  specs (in JS) in order to replicate the navigation behavior of portal
  users.

**Migration to Odoo 19.0 (in progress)** — port work is tracked via OPTIDEEP
Sprint S20 on OCA/helpdesk fork [optideep/helpdesk, branch
`19.0-mig-helpdesk_mgmt`]. Known areas to audit during the port:
portal controllers (`controllers/main.py`, `controllers/myaccount.py`),
OWL 2 assets (`static/src/js/new_ticket.esm.js`, dashboard kanban view),
`ir_http.py` override, Python tests common fixtures, JS tests framework.
