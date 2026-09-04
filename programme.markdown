---
layout: page
title: "Programme"
permalink: /programme/
footer: false
---

<style>
.schedule-wrap { overflow-x: auto; }
.schedule {
  table-layout: fixed;
  min-width: 44em;
  border-collapse: collapse;
  font-size: .92em;
}

.schedule th,
.schedule td {
  vertical-align: top;
  padding: .5em .7em;
  overflow-wrap: break-word;
}

.schedule tr:nth-child(even) { background-color: transparent; }

.schedule thead th {
  vertical-align: bottom;
  text-align: left;
  font-size: .95em;
}

.schedule .time {
  white-space: nowrap;
  color: #757575;
  font-variant-numeric: tabular-nums;
}

.schedule td strong {
  display: block;
  margin-bottom: .15em;
  color: #111;
}

.schedule .talk { color: #555; }

.schedule tr.session td {
  background-color: #eef4fc;
  border-top: 2px solid #c9dcf5;
  padding-top: .45em;
  padding-bottom: .45em;
  font-size: .82em;
  font-weight: 600;
  letter-spacing: .05em;
  text-transform: uppercase;
  color: #1b5bab;
}

.schedule tr.pause td {
  text-align: center;
  color: #757575;
  font-size: .88em;
}
.schedule tr.pause td.time { text-align: left; }

.schedule tr.evening td { border-top: 2px solid #d8d8d8; }
</style>

Below, you find the preliminary schedule. Talks and times may still change.

<div class="schedule-wrap" markdown="0">
<table class="schedule">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="24%" />
<col width="24%" />
<col width="24%" />
</colgroup>
<thead>
<tr class="header">
<th>Time/Day</th>
<th>Tuesday<br/>6th Oct</th>
<th>Wednesday<br/>7th Oct</th>
<th>Thursday<br/>8th Oct</th>
<th>Friday<br/>9th Oct</th>
</tr>
</thead>
<tbody>
<tr class="pause">
<td class="time" markdown="span">10:00 - 10:30</td>
<td markdown="span"></td>
<td markdown="span">Coffee</td>
<td markdown="span">Coffee</td>
<td markdown="span">Coffee</td>
</tr>
<tr class="session">
<td class="time" markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">1 Verification</td>
<td markdown="span">4 “Events”</td>
<td markdown="span">7 Twins+Types</td>
</tr>
<tr>
<td class="time" markdown="span">10:30 - 11:15</td>
<td markdown="span"></td>
<td class="talk" markdown="span">**Reiner Hähnle**Welcome and Information</td>
<td class="talk" markdown="span">**Rudolf Schlatte**The year in ABS</td>
<td class="talk" markdown="span">**S. L. Tapia Tarifa**Data Protection Principles for Digital Twins</td>
</tr>
<tr>
<td class="time" markdown="span">11:15 - 12:00</td>
<td markdown="span"></td>
<td class="talk" markdown="span">**Frank de Boer**Deductive Verification for Actors</td>
<td class="talk" markdown="span">**Michele Loreti**Qualitative and Quantitative Monitoring of Event Systems</td>
<td class="talk" markdown="span">**Einar B. Johnsen**TBA</td>
</tr>
<tr>
<td class="time" markdown="span">12:00 - 12:45</td>
<td markdown="span"></td>
<td class="talk" markdown="span">**Niklas Heidler**Specifying and Verifying with Trace Formulas</td>
<td class="talk" markdown="span">**Cosimo Laneve**The Stipula Experience</td>
<td class="talk" markdown="span">**Violet Ka I Pun**Type-based information flow analysis for actors</td>
</tr>
<tr class="pause">
<td class="time" markdown="span">12:45 - 14:00</td>
<td markdown="span"></td>
<td markdown="span">Lunch</td>
<td markdown="span">Lunch</td>
<td markdown="span">Lunch</td>
</tr>
<tr class="session">
<td class="time" markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">2 Features</td>
<td markdown="span">5 Aggregates</td>
<td markdown="span">End of APM</td>
</tr>
<tr>
<td class="time" markdown="span">14:00 - 14:45</td>
<td markdown="span"></td>
<td class="talk" markdown="span">**Crystal Din**Modular soundness checking of feature model evolution plans</td>
<td class="talk" markdown="span">**Ferruccio Damiani**Multi-party Aggregate Programming: Heterogeneous Collectives</td>
<td markdown="span"></td>
</tr>
<tr>
<td class="time" markdown="span">14:45 - 15:30</td>
<td markdown="span"></td>
<td class="talk" markdown="span">**Maurice ter Beek**Families of RTS</td>
<td class="talk" markdown="span">**Marco Scaletta**An LAGC Semantics for XC</td>
<td markdown="span"></td>
</tr>
<tr class="pause">
<td class="time" markdown="span">15:30 - 16:00</td>
<td markdown="span"></td>
<td markdown="span">Break</td>
<td markdown="span">Break</td>
<td markdown="span"></td>
</tr>
<tr class="session">
<td class="time" markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">3 Protocols</td>
<td markdown="span">6 Asynchronicity</td>
<td markdown="span"></td>
</tr>
<tr>
<td class="time" markdown="span">16:00 - 16:45</td>
<td markdown="span"></td>
<td class="talk" markdown="span">**Tobias Wrigstad**Protocols and Behavior-oriented Concurrency</td>
<td class="talk" markdown="span">**Ludovic Henrio**Tail Modulo Async-Await</td>
<td markdown="span"></td>
</tr>
<tr>
<td class="time" markdown="span">16:45 - 17:30</td>
<td markdown="span"></td>
<td class="talk" markdown="span">**Ragnar Mogk**Protocols and Algebraic Replicated DT</td>
<td class="talk" markdown="span">**Daniel Drodt**A Complete, Formal Semantics for Async Rust</td>
<td markdown="span"></td>
</tr>
<tr class="evening">
<td class="time" markdown="span">Evening</td>
<td class="talk" markdown="span">**Reception**18:00<br/>[Vinoteca Carroccia](https://www.facebook.com/people/Vinoteca-Carroccia/100090145849713/)</td>
<td markdown="span"></td>
<td class="talk" markdown="span">**Workshop Dinner**19:00<br/>[Ferrucci Wine Bar](http://ferrucci-winebar.de)</td>
<td markdown="span"></td>
</tr>
</tbody>
</table>
</div>
