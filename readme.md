# Description

this project is an attempt at making an out of order superscalar CPU in Logisim Evolution

# Instruction Set

<table>
    <tr>
        <th>Opcode (hex)</td>
        <th>Opcode (bin)</td>
        <th>Arguments format</th>
        <th>Name</th>
        <th>Description</th>
        <th>Example (hex)</th>
    </tr>
    <tr>
        <td>40</td>
        <td>01000000</td>
        <td>dest[4] empty[4] const[16]</td>
        <td>MOV</td>
        <td>store lower 16bits of a constant in the Dest register</td>
        <td>401000FF</td>
    </tr>
</table>