# How-To-Move-The-Divi-Blurb-Module-Title-Above-The-Image
How To Move The Divi Blurb Module Title Above The Image
<script>
jQuery(document).ready(function() {
jQuery(".pa-move-blurb-title").each(function () {
 var modhead = jQuery(this).find('.et_pb_module_header')
 var modimg = jQuery(this).find('.et_pb_main_blurb_image');
      jQuery(modhead).prependTo(modimg);
});
});
</script>
