<script lang="ts">

</script>

<style lang="scss">
@use "@material/theme";
@use 'material-bottom-nav/bottom-nav' as bottom-nav;

.bottom-nav {
  @include bottom-nav.root(
    $background-color: $primary,
    $active-color: #FFFFFF,
    $inactive-color: #E0E0E0
  );
}
</style>

<nav class="bottom-nav mdc_theme--primary">
    <a class="bottom-nav__destination" href="#">
      <svg class="bottom-nav__icon" viewBox="0 0 24 24">
        <path d="M11,7V12.11L15.71,14.9L16.5,13.62L12.5,11.25V7M12.5,2C8.97,2 5.91,3.92 4.27,6.77L2,4.5V11H8.5L5.75,8.25C6.96,5.73 9.5,4 12.5,4A7.5,7.5 0 0,1 20,11.5A7.5,7.5 0 0,1 12.5,19C9.23,19 6.47,16.91 5.44,14H3.34C4.44,18.03 8.11,21 12.5,21C17.74,21 22,16.75 22,11.5A9.5,9.5 0 0,0 12.5,2Z"></path>
      </svg>
      <span class="bottom-nav__label">ACCOUNT</span>
    </a>
  
    <a class="bottom-nav__destination bottom-nav__destination--active" href="#">
      <svg class="bottom-nav__icon" viewBox="0 0 24 24">
        <path d="M12,21.35L10.55,20.03C5.4,15.36 2,12.27 2,8.5C2,5.41 4.42,3 7.5,3C9.24,3 10.91,3.81 12,5.08C13.09,3.81 14.76,3 16.5,3C19.58,3 22,5.41 22,8.5C22,12.27 18.6,15.36 13.45,20.03L12,21.35Z"></path>
      </svg>
      <span class="bottom-nav__label">ISSUES</span>
    </a>
  </nav>