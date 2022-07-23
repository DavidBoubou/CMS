 Synchronization for exportation:
 

Re,
je me suis plongé dans l'anglais et après plusieurs tentatives, j'ai une solution. La voici pour ceux qui auraient le même soucis :
-> créer le dossier "sync" où vous souhaitez. Pour moi : "web/sites/default/" ;
-> faire un chown pour que le dossier vous appartiennent ainsi qu'à votre groupe ;
-> éditer le fichier settings.php présent dans le dossier "web/sites/default/". En fin de fichier, modifier la valeur de "$config_directories['sync'] = '". Dans mon cas, cela donne : "$config_directories['sync'] = 'sites/default/sync';"

Je suis preneur d'explications du pourquoi car je n'ai pas tout compris.

Merci


 crons:
 http://elixirv2.dd:8083/cron/2qTvL_aqpwyvWTKCH4bGWEXmCOTGhRzumiQ8U2E3dM0AWRZPuC7WtZ0x5VTJwlhoFLGYNoMfJQ
