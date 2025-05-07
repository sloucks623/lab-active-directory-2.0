# Group Policy Objects – AD Lab 2.0

This section tracks all GPOs created and linked within the Active Directory Lab 2.0 environment.

---

## GPO Summary Table

| GPO Name              | Linked OU       | Purpose                                | Export File         |
|-----------------------|-----------------|----------------------------------------|----------------------|
| `Baseline Workstation`| `Domain Users`  | Disable Cortana, set wallpaper         | `baseline-wks.gpo`   |
| `Password Policy`     | `Default Domain`| Enforce complex passwords, 45-day max  | `password-policy.gpo`|
| `Admin Lockdown`      | `IT Admins`     | Remove access to Control Panel, etc.   | `admin-lockdown.gpo` |

---

## Notes

- All exported `.gpo` files will be placed in this folder
- Each policy should include a screenshot in the `screenshots/` folder
- Use `Group Policy Management Console (GPMC)` to back up and export

---

## To Do

- [ ] Create GPOs in DC2 using GPMC
- [ ] Export using “Back Up All GPOs” and copy into `/gpos/`
- [ ] Link policies to correct OUs
- [ ] Document changes here as implemented
