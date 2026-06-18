```mermaid
gantt
    title KD3CKD Summer 2026 Roadmap
    Next Meeting w/ KD8OXT :vert, 2026-06-25, 0d
    dateFormat YYYY-MM
section Milestones
        Dayton Hamvention       : milestone, hamvention, 2026-05-15, 2d
        ARRL Field Day       : milestone, fieldday, 2026-06-27, 2d
        CEDAR Workshop    : milestone, CEDAR, 2026-06-08, 1w 
        Iceland/Spain Eclipse       : milestone, Eclipse, 2026-07-12, 1d
        EM Out of Office : emoof, 2026-07-20, 5d
        GP Out of Office : gpoof, 2026-06-20, 5d
        Departure       : milestone, end, 2026-08-01, 1d
                                
section Documentation
       RSEAV-1 Testing    :done, antennatest, 2026-05-1, 20d
       RSEAV-1 Documentation    :antennadoc, after antennatest, 25d
       HF Receiver Documentation    :rx888doc, 2026-06-18, 25d
       Update HamSCI Getting Started Documentation    :introduc, 2026-06-18, 25d
       HardwareX Draft :hardwarex, 2026-06-11, 30d
section RX888 PSWS Shipping
       Meet with Design Dept. :done, designmeet, 2026-05-01, 1d
       Finalize box design: boxdesign, 2026-06-05, 1d
       Order boxes: boxorder, after boxdesign, 7d
       Finalize shipping BOM: BOM, 2026-05-05, 5d
       Pack and ship boxes: packing, after BOM boxorder, 5d
       Ship!: ship, after packing, 2d
       Shipping Deadline      :milestone, shippingdeadline, 2026-07-01, 1d
section Magnetometer
       Calm US Postal Service:done, notabom, 2026-06-01, 2w
       Magnetometer Meeting: magmeet, 2026-06-11, 1d
       Magnetometer Testing: magtest, after magmeet, 1w
       Magnetometer Packing: magpack, after magtest, 1w
       Magnetometer Shipping: magship, after magpack, 2d
section VLF Shipping
       VLF logistics: vlflog, after shippingdeadline, 2w
       VLF Shipping: vlfship, after vlflog, 2d
section WSPRSonde
       WSPRSonde packing: done, wsprsondepack, 2026-06-01, 5d
       WSPRSonde letter: wsprsondeletter, 2026-06-04, 2d
       WSPRsonde map: wsprsondemap, after wsprsondeletter, 7d
       Ship WSPRsondes: wsprship, after wsprsondepack wsprsondemap, 2d
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
- Box design updates (and PSWS logo)
- HardwareX manuscript - adapt documentation from https://github.com/K3DFD-Radio/K3DFD-PSWS
- Smart outlet spec (https://github.com/HamSCI/psws-charette/issues/46)
