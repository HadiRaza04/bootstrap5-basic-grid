# <a href="https://www.w3schools.com/bootstrap5/bootstrap_grid_basic.php" target="_blank">BootStrap5-Basic-Grid</a>
<h2>Bootstrap5 basic-grid practice from <a href="https://www.w3schools.com/" target="_blank">w3schools</a>.</h2>

1) Bootstrap's grid system is built with flexbox and allows up to 12 columns across the page.

2) The Bootstrap 5 grid system has six classes:
<ul><li><b>.col</b>   (extra small devices - screen width less than 576px)</li><li><b>.col-sm</b>   (small devices - screen width equal to or greater than 576px)
</li><li><b>.col-md</b>   (medium devices - screen width equal to or greater than 768px)</li><li><b>.col-lg</b>   (large devices - screen width equal to or greater than 992px)</li><li><b>.col-xl</b>  (xlarge devices - screen width equal to or greater than 1200px)</li><li><b>.col-xxl</b>  (xxlarge devices - screen width equal to or greater than 1400px)</li></ul>

3) First example: create a row <b>(<div class="row">)</b>. Then, add the desired number of columns (tags with appropriate <b>.col-*-* classes</b>). The first star (*) represents the responsiveness: <b>sm, md, lg, xl or xxl</b>, while the second star represents a number, which should add up to 12 for each row.

4) Second example: instead of adding a number to each col, let bootstrap handle the layout, to create equal width columns: two "col" elements = 50% width to each col, while three <b>cols = 33.33%</b> width to each col. Four <b>cols = 25%</b> width, etc. You can also use <b>.col-sm|md|lg|xl|xxl</b> to make the columns responsive.
