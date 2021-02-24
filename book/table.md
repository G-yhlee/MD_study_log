
<table>
  <tr>
    <th colspan="4">A 영역</td>
    <td rowspan="3">rowspan3</td>
    <th colspan="2">c 영역</td>
    <th colspan="2">D 영역</td>
  </tr>
  <tr>
    <td>A11</td><td>A12</td><td>A13</td><td>A14</td>
    <td>C11</td><td>C12</td>
    <td>D11</td><td>D12</td>
  </tr>  
  <tr>
    <td>A21</td><td>A22</td><td>A23</td><td>A24</td>
    <td>C21</td><td>C22</td>
    <td>D21</td><td>D22</td>
  </tr>  
  
  <tr>
      <td colspan="4">colspan4</td>
      <td colspan="5">colspan5</td>
  </tr>
</table>


```html
<!-- 복잡한 표는 html 로 작성 가능하다  -->
<!-- table, tr , td, colspan, rowspan 5 가지만 알면 끝. -->

<table>
  <tr>
    <td colspan="4">A 영역</td>
    <td rowspan="3">rowspan3</td>
    <td colspan="2">c 영역</td>
    <td colspan="2">D 영역</td>
  </tr>
  <tr name="첫번재 줄">
    <td>A11</td><td>A12</td><td>A13</td><td>A14</td>
    <td>C11</td><td>C12</td>
    <td>D11</td><td>D12</td>
  </tr>  
  <tr name="두번째 줄">
    <td>A21</td><td>A22</td><td>A23</td><td>A24</td>
    <td>C21</td><td>C22</td>
    <td>D21</td><td>D22</td>
  </tr>  
  
  <tr name="마지막 줄">
      <td colspan="4">colspan4</td>
      <td colspan="5">colspan5</td>
  </tr>
</table>
```