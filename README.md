# Refactored Digital Navigation Tool

### Track symbol (***example for simulation***)
The following table describes the track label - type of ***sim*** - fields.
<table>
<tr>
<th colspan="2">Track Symbol Presentation</th>
</tr>
<tr>
    <td colspan="2">Default label presentation without active input fields</td>
</tr>
<tr><td colspan="2" align="center"><img src="doc/img/ATCUI_sim_label.png"></td></tr>
<tr>
    <th>Id</th>
    <th>Description</th>
</tr>
<tr>
    <td align="center">1</td>
    <td>Alert text: UI.UpdateTRACK({..., alert: [0,1,2,3,4,5,6,7]})</td>
</tr>
<tr>
    <td align="center">2</td>
    <td>Attitude indicator: UI.UpdateTRACK({..., attitude: [-1,0,1]})</td>
</tr>
<tr>
    <td align="center">3</td>
    <td>Callsign: UI.UpdateTRACK({..., callsign: "new callsign"})</td>
</tr>
<tr>
    <td align="center">4</td>
    <td>Entry level: UI.UpdateTRACK({..., efl: [0..660]})</td>
</tr>
<tr>
    <td align="center">5</td>
    <td>Actual level: UI.UpdateTRACK({..., cfl: [0..660]})*</td>
</tr>
<tr>
    <td align="center">6</td>
    <td>Exit level: UI.UpdateTRACK({..., xfl: [0..660]})</td>
</tr>
<tr>
    <td align="center">7</td>
    <td>COPN: UI.UpdateTRACK({..., copn: "copn"})</td>
</tr>
<tr>
    <td align="center">8</td>
    <td>COPX: UI.UpdateTRACK({..., copx: "copx"})**</td>
</tr>
<tr>
    <td colspan="2">** <em>Clicking on the COPX field, the heading selector window pops up. See below the sample.</em></td>
</tr>
<tr>
    <td colspan="2" align="center">
        <img src="doc/img/ATCUI_hdgselector.png">
    </td>
</tr>
<tr>
    <td align="center">9</td>
    <td>Track position indicator</td>
</tr>
<tr>
    <td align="center">10</td>
    <td>Track heading indicator - if available</td>
</tr>
<tr>
    <td align="center">11</td>
    <td>Label stick</td>
</tr>
<tr>
    <td colspan="2">* Default label presentation with active input fields - <b>CFL</b> input</td>
</tr>
<tr>
    <td colspan="2" align="center">
        <img src="doc/img/ATCUI_clfinput.png">
        <img src="doc/img/ATCUI_clfinput_ram.png">
        <img src="doc/img/ATCUI_clfinput_alert.png">
    </td>
</tr>
<tr>
    <td align="center">12</td>
    <td>Label CFL input list</td>
</tr>
</table>
