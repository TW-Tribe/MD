## Table
Making tables using markdown short codes and HTML codes

Tables represent *Container Blocks* in Markdown. You can create a plain  table using Markdown short codes or else use HTML tags inside a Markdown file.

### Using Markdown Short Codes

Name | Place | Profession   
---- | ---- | ----   
Saina | Hyderabad | Badminton Player
Messi | Barcelona | Soccer Player

Add a colon to left, right or both sides of header row to change alignment of text.

Name | Place | Profession   
:---- | :----:| ----:   
Saina | Hyderabad | Badminton Player
Messi | Barcelona | Soccer Player

#### Highlights

* Add as many columns or rows.
* Lesser properties when compared to HTML tables.
* Cannot use color or nested elements inside the cells.

### Using HTML codes

Note: You cannot use Markdown short codes inside HTML tags.

<table class="table table-striped">
<caption>Caption for this Table</caption>
<thead class="thead-dark">
<tr>
    <th width="30%">Property</th>
    <th width="70%">Description</th>
    </tr>
</thead>
<tbody>
<tr>
    <td>Topic1</td>
    <td>Topic2
        <ul>
        <li>Bullet item</li>
        <li>Bullet item</li>
        </ul>
        </td>
    </tr>
<tr>
    <td>TopicA</td>
    <td>TopicB</td>
    </tr>
</tbody>
</table>