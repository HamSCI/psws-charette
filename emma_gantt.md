```mermaid
gantt
    title KD3CKD Summer 2026 Roadmap
    Next Meeting w/ KD8OXT :vert, 2026-05-11, 0d
    dateFormat YYYY-MM
section Milestones
        Dayton Hamvention       : milestone, hamvention, 2026-05-15, 2d
        ARRL Field Day       : milestone, fieldday, 2026-06-27, 2d
        CEDAR Workshop    : milestone, CEDAR, 2026-06-21, 1d 
        Iceland/Spain Eclipse       : milestone, Eclipse, 2026-07-12, 1d
        EM Out of Office : oof, 2026-07-20, 5d
        Departure       : milestone, end, 2026-08-01, 1d
                                
section Documentation
       RSEAV-1 Testing    :antennatest, 2026-05-1, 20d
       RSEAV-1 Documentation    :antennadoc, after antennatest, 5d
       HardwareX Draft :hardwarex, after antennatest, 30d
section PSWS Shipping
       Meet with Design Dept. :done, designmeet, 2026-05-01, 1d
       Finalize box design: boxdesign, 2026-05-15, 1d
       Order boxes: boxorder, after boxdesign, 7d
       Finalize BOM: BOM, 2026-05-05, 5d
       Pack and ship boxes: packing, after BOM boxorder, 5d
       Ship!: ship, after packing, 2d
       Shipping Deadline      :milestone, shippingdeadline, 2026-07-01, 1d
section VLF Shipping
       VLF logistics: vlflog, after shippingdeadline, 2w
       VLF Shipping: vlfship, after vlflog, 2d

```
## TO-DO List
- [X] Start a to-do list
- [X] Order antenna and timing injectors
- [ ] Order parts 
- [ ] Get status updates on all the instruments!
    - [ ] WSPRsonde
    - [ ] Ground mag
    - [ ] Antenna and timing injectors

      

## KD3CKD/KD8OXT - Agenda items for next meeting
- Ticketing system
- RX888 updates
- Box design updates (and PSWS logo)
- HardwareX manuscript
- Smart outlet spec (https://github.com/HamSCI/psws-charette/issues/46)
