# Brevent-fps-boost

cmd package compile -m speed -f <package.name>

cmd package bg-dexopt-job

cmd device_config put game_overlay <package.name> mode=2,fps=120:mode=3,fps=30

cmd game mode set performance <package.name>

cmd game downscale 90 <package.name>

cmd activity set-inactive <package.name> false
