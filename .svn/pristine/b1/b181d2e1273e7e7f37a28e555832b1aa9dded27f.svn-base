# EasyImport

QGIS Plugin to import gps data from ascii directly to corresponding layers

This actual version is calibrated to deal with Pully's codes for gps inputs into the Qwat project database

Read more abour QWAT project here : https://github.com/qwat/QWAT

This code could be made more generic an be useful for any gps import into qgis.

Once this generic goal will be achieved, we we'll be able to upload it as a generic Qgis plugin in the official qgis plugin repository :

See https://plugins.qgis.org/ for more infos about qgis plugins

How to set your config gps codes. In the config.xml file, just add blocks as described here :

            <pointlayer code="300">
                <!-- Nom de la couche de destination dans le projet QGis (case sensitiv...) -->
                <destinationlayer>points de construction</destinationlayer>
                <colummappings>
                    <columnmapping>
                        <!-- Nom de la colonne du fichier de données source -->
                        <source>Point_ID</source>
                        <!-- Nom de la colonne de la couche QGis de destination -->
                        <destination>id</destination>
                        <!-- Regex permettant de ne garder que la partie numérique de la donnée source -->
                        <!-- Pour faire un autre regex voir www.debuggex.com et https://docs.python.org/2/howto/regex.html#non-capturing-and-named-groups -->
                        <!-- le groupe à captuer doit s'appeler "group" -->
                        <regex>^(?P&lt;group&gt;\d*)</regex>
                    </columnmapping>
                    <columnmapping>
                        <!-- Nom de la colonne du fichier de données source -->
                        <source>Ortho_Heig</source>
                        <!-- Nom de la colonne de la couche QGis de destination -->
                        <destination>altitude</destination>
                    </columnmapping>
                </colummappings>
            </pointlayer>
