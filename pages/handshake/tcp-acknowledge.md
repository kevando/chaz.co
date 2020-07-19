---
layout: handshake
permalink: /empathy-handshake/tcp-acknowledge
title: TCP Handshake | Send

current_step: 1

left_icon: 🤖
right_icon: 🤖

url:
  sends:  /empathy-handshake/tcp-receive
  receives:  /empathy-handshake/tcp-acknowledge
  acknowledges:  /empathy-handshake/tcp-acknowledge

---

f

### Robot 1 [sends]({{ page.url.sends }}) a packet. 

### Robot 2 [receives]({{ page.url.receives }}) that packet.

### Robot 2 [acknowledgess]({{ page.url.acknowledges }}) that packet.

---

# Acknowledgement