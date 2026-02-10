---
layout: page
title: "Derive"
permalink: /software/pcx86/app/other/derive/2.60/
machines:
  - id: ibm5160-vga
    type: pcx86
    config: /machines/pcx86/ibm/5160/vga/640kb/debugger/machine.xml
    resume: 1
    state: state.json
    autoMount:
      A:
        name: MS-DOS 3.30 (Disk 1)
      B:
        name: Derive 2.60
    autoType: $date\r$time\rB:\rdir\rderive\r
---
{% include machine.html id="ibm5160-vga" %}
