# Cut it!
Mono repo root of Cut it! projects

## Command example
python3 /usr/share/inkscape/extensions/sendto_silhouette.py --dry_run=True --preview=False --strategy=zorder --cmdfile=/app/cutit_backend/tmp/models/back_cover_a52s_5g.cmd /app/cutit_backend/tmp/models/back_cover_a52s_5g.svg

## Initial config
x_off: '0',
y_off: '15',
cuttingmat: 'no_mat',
toolholder: '1',
tool: 'default',
media: '134',
speed: '10',
pressure: '20',
depth: '-1',
multipass: '1',
endposition: 'start',
regwidth: '180',
reglength: '230',
regoriginx: '15',
regoriginy: '20',
sharpencorners_start: '0.1',
sharpencorners_end: '0.1',
overcut: '0.5',
strategy: 'zorder',

## Failing models
1. "BACK COVER NIN SWITCH LITE (plug tablette)" (category=AUTRES) --> Solved removing parenthesis
