# <a href="https://www.w3schools.com/bootstrap5/bootstrap_grid_basic.php" target="_blank">BootStrap5-Basic-Grid</a>
<h2>Bootstrap5 basic-grid practice from <a href="https://www.w3schools.com/" target="_blank">w3schools</a>.</h2>

1) Bootstrap's grid system is built with flexbox and allows up to 12 columns across the page.

2) The Bootstrap 5 grid system has six classes:
<ul><li>.col   (extra small devices - screen width less than 576px)</li><li>.col-sm   (small devices - screen width equal to or greater than 576px)
</li><li>.col-md   (medium devices - screen width equal to or greater than 768px)</li><li>.col-lg   (large devices - screen width equal to or greater than 992px)</li><li>.col-xl  (xlarge devices - screen width equal to or greater than 1200px)</li><li>.col-xxl  (xxlarge devices - screen width equal to or greater than 1400px)</li></ul>

3) First example: create a row (<div class="row">). Then, add the desired number of columns (tags with appropriate .col-*-* classes). The first star (*) represents the responsiveness: sm, md, lg, xl or xxl, while the second star represents a number, which should add up to 12 for each row.

4) Second example: instead of adding a number to each col, let bootstrap handle the layout, to create equal width columns: two "col" elements = 50% width to each col, while three cols = 33.33% width to each col. Four cols = 25% width, etc. You can also use .col-sm|md|lg|xl|xxl to make the columns responsive.
