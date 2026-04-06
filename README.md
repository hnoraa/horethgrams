# horethgrams
A nonogram app

## Sample data structure
<small>This is subject to change</small>
```json
{
    "name": "sample",
    "palette": [
      {
        "color": "black",
        "hex": "FFFFFF"
      }
    ],
    "size": {
      "width": 4,
      "height": 4
    }
    "columns": [
      { "data": [1,1] },
      { "data": [1,2] },
      { "data": [1,2] },
      { "data": [3] },
    ],
    "rows": [
      { "data": [3] },
      { "data": [1] },
      { "data": [3] },
      { "data": [4] },
    ],
}
```
Would produce this:

<table>
  <tr>
    <td></td>
    <td>1</td>
    <td>1</td>
    <td>1</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>1</td>
    <td>2</td>
    <td>2</td>
    <td>3</td>
  </tr>
  <tr>
    <td>3</td>
    <td>x</td>
    <td>x</td>
    <td>x</td>
    <td></td>
  </tr>
  <tr>
    <td>1</td>
    <td></td>
    <td></td>
    <td></td>
    <td>x</td>
  </tr>
  <tr>
    <td>3</td>
    <td></td>
    <td>x</td>
    <td>x</td>
    <td>x</td>
  </tr>
  <tr>
    <td>4</td>
    <td>x</td>
    <td>x</td>
    <td>x</td>
    <td>x</td>
  </tr>
</table>
