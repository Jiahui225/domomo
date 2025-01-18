# domomo
damomo_user_inrerface

<script>
  <script>
    window.RufflePlayer = window.RufflePlayer || {};
    window.addEventListener("load", (event) => {
        const ruffle = window.RufflePlayer.newest();
        const player = ruffle.createPlayer();
        const container = document.getElementById("container");
        container.appendChild(player);
        player.ruffle().load("damomo_ui.swf");
    });
</script>
<script src="Dowloads\DamomoUI\damomo_ui.swf"></script>
</script>
