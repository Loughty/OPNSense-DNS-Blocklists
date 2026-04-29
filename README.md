# OPNSense-DNS-Blocklists

##### ESPAÑOL:

Aquí voy a poner las listas de bloqueos que yo uso con el Unbound DNS en OPNSense. Usualmente RRSS y otras cosas que no suelen estar incluidas en las listas de bloqueo que ya vienen con el OPNSense. Gracias al post del usuario Fright en el foro de OPNSense pude descubrir que las listas de URL en el OPNSense suportan wildcards, cosa que fácilita bastante el trabajo.
https://forum.opnsense.org/index.php?topic=37559.0

Sientanse libres de compartir en Issues o Discussions sus correcciones, sugerencias o incluso sus propias listas en caso de que quieran que las añada.

##### ENGLISH:

Here I'm gonna put the blocklists that I use for the Unbound DNS in OPNSense. Usually are social media and others things that are not covered on the build-in blocklists that OPNSense alreade have. Thanks to the post of the user Fright in the OPNSense Forum, I know that the OPNSense support wildcards on the URL lists, thing that make the work a lot easier.
https://forum.opnsense.org/index.php?topic=37559.0

Please feel free to share on Issues or Discussions ur corrections, suggestions and even ur own lists if u want to be added here.

#### COMO USAR / HOW TO USE:
1. RAW
<img width="1420" height="306" alt="Captura desde 2026-04-29 14-27-59" src="https://github.com/user-attachments/assets/66a60ab9-8199-467a-b229-d8056969274b" />
2. Copy
<img width="825" height="256" alt="Captura desde 2026-04-29 14-28-20" src="https://github.com/user-attachments/assets/ff5b19a8-3b66-48e7-aa69-bc00a230af2a" />
3. → "advance mode"
<img width="1184" height="670" alt="Captura desde 2026-04-29 14-30-01" src="https://github.com/user-attachments/assets/e3de8829-597f-4070-9795-2fe132e3f99c" />
4. Save & Apply

#### EJEMPLOS / EXAMPLES:
https://raw.githubusercontent.com/hagezi/dns-blocklists/refs/heads/main/wildcard/doh.txt

- Basically is:
```
*.domain.com
```
- Still can block only the subdomain, in cases where blocking the whole domain is not recommended:
```
sub.domain.com
```

