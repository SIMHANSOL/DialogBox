# DialogBox
🧱 Give the text a variety of effects.<br>
⛏ The library used to create the game has been converted for JS.

<br>

> What can i do? 🤔
> - Indication Delay
> - Change Color Animation
> - Change Transparency Animation
> - Typing Animation
> - Shaking Animation
> - Wave Animation
> - Rotation Animation

<br>

## Table of contents
- [Functions](#Functions)
- [Getting Started](#Getting-Started)

<br>

## Functions
Commands
<table>
    <thead>
        <tr>
            <th align="left">Name</th>
            <th align="left">Command</th>
            <th align="left">Default</th>
            <th align="left">Ex</th>
        </tr>
    </thead>
    <tbody>
        <tr>
          <td align="left"><b>C</b>olor</td>
          <td align="left">-</td>
          <td align="left">inherit</td>
          <td align="left">-</td>
        </tr>
        <tr>
            <td align="left">Alpha</td>
            <td align="left">|A0.5|</td>
            <td align="left">1.0</td>
            <td align="left">-</td>
        </tr>
        <tr>
            <td align="left">Delay</td>
            <td align="left">|D10|</td>
            <td align="left">-</td>
            <td align="left">-</td>
        </tr>
        <tr>
            <td align="left">Type</td>
            <td align="left">
              <ol padding-left="1em">
                <li>normal</li>
                <li>wiggle</li>
                <li>piston wiggle</li>
                <li>wave</li>
                <li>piston wave</li>
                <li>rotate wave</li>
                <li>wave + wiggle</li>
              </ol>
            <td align="left">-</td>
            <td align="left">-</td>
        </tr>
        <tr>
            <td align="left">Force</td>
            <td align="left">-</td>
            <td align="left">-</td>
            <td align="left">-</td>
        </tr>
        <tr>
            <td align="left">Speed</td>
            <td align="left">-</td>
            <td align="left">-</td>
            <td align="left">-</td>
        </tr>
        <tr>
            <td align="left">Event</td>
            <td align="left">-</td>
            <td align="left">-</td>
            <td align="left">-</td>
        </tr>
    </tbody>
</table>

<br>

## Getting Started
```javascript
TextDialog("HI.|D10| my name is|S0.5|....|S1| |D10|Sim-Hansol.");
```

🎉 <b>You can insert a command into a string.</b>
