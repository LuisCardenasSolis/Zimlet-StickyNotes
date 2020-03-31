# Zimlet-StickyNotes

![Preview](https://mail.perulinux.pe/service/home/~/?auth=co&loc=es&id=47329&part=2.2)

## Deplegar zimlet:
~~~
 git clone
 /opt/zimbra/bin/zmzimletctl createZip ${PWD}/com_zimbra_stickynotes
 /opt/zimbra/bin/zmzimletctl deploy com_zimbra_stickynotes.zip
 /opt/zimbra/bin/zmprov fc zimlet
~~~

- Verificar que el zimlet este activado en el COS
