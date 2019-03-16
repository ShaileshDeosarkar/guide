---
title: Change Text Inside an Element Using jQuery
---
## Change Text Inside an Element Using jQuery

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
<script>
  $(document).ready(function() {
    $("#target1").css("color", "red");
    var text = $("#target4").text();
       $("#target4").html("<em>"+text+" </em>");
  });
</script>
