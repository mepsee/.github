<div align="center">

# mepsee

High-level Styling Language, for Web and Native.

</div>

## Main Characteristics

- Modular Stdlib Design: in CSS, font style, box style, text layout, and more concerns can be mixed easily. Managing this complexity is important. so we categorize it by concerns.
  <table>
  <tbody>
  <tr>
  <td>

  ```css
  .test {
    font-weight: 400;
    border: 1px solid black;
    font-family: "Times New Roman", sans-serif;
  }
  ```

  </td>
  <td>

  ```
  test {
    font = (
      weight: 400,
      family: ["Times New Roman", sans-serif],
    );
    border = (stroke: black.solid * 1px);
  }
  ```
  
  </td>
  </tr>
  </tbody>
  </table>
- Layout Coordinates with Script: TBD

## Why is the name mepsee?

We caught up on the naming idea from 맵시(meaning *style* in Korean); its actual Romanization is "maepsi", but "mepsee" serves similar pronunciation and seems great.
