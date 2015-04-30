# cd-parent

Build fails with this call (since versions:set runs on the submodules as well)
    mvn -Psetversions validate
    
But succeeds with (versions:set only runs on parent)
    mvn versions:set -DnewVersion=1.0.0
