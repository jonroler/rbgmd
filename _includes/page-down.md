<script>

$('#page-down,#page-down2').click(function(){
    $("html, body").animate({ scrollTop: $(window).height()}, 600);
    return false;
});

</script>