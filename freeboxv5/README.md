Usage :

Place the script somewhere, /usr/local/share/munin/plugins for example.
Then :
  for i in uptime CRC HEC FEC attenuation debitatm debitethernet debitswitch debitusb debitwan margebruit
  do
      ln -s /usr/local/share/munin/plugins/freebox_ /etc/munin/plugins/freebox_$i
  done

Restart munin-node

DONE.
