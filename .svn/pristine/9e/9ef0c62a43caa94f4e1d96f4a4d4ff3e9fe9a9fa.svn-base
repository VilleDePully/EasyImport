# -*- coding: utf-8 -*-
"""
/***************************************************************************
 EasyImport
                                 A QGIS plugin
 EasyImport
                             -------------------
        begin                : 2015-01-16
        copyright            : (C) 2015 by Ville de Pully
        email                : informatique@pully.ch
        git sha              : $Format:%H$
 ***************************************************************************/

/***************************************************************************
 *                                                                         *
 *   This program is free software; you can redistribute it and/or modify  *
 *   it under the terms of the GNU General Public License as published by  *
 *   the Free Software Foundation; either version 2 of the License, or     *
 *   (at your option) any later version.                                   *
 *                                                                         *
 ***************************************************************************/
 This script initializes the plugin, making it known to QGIS.
"""


# noinspection PyPep8Naming
def classFactory(iface):  # pylint: disable=invalid-name
    """Load EasyImport class from file EasyImport.

    :param iface: A QGIS interface instance.
    :type iface: QgsInterface
    """
    #
    from .EasyImport import EasyImport
    return EasyImport(iface)
