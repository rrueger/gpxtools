# GPX Tools

This project includes a simple portable `bash` script that which combine
multiples GPX files (in order) into one single `.gpx` file and writes this to
`stdout`.

How to use `gpx-combine`

    bash gpx-combine <FILE 1> <FILE 2> [FILE N...] > combined.gpx

or do the usual and make the script executable to then call it

    chmod +x gpx-combine
    ./combine-gpx  <FILE 1> <FILE 2> [FILE N...] > combined.gpx

Finally, the script can be added to your `$PATH` so it can be called from
anywhere: add

    export PATH=$PATH:<Path to gpx-combine>

to your shell initialisation file (e.g. `~/.bashrc`).

### Why another GPX tool?

This project was born out of a shortcoming of my cycling computer: to upload a
new route naviagation whilst riding you must stop the recording, synchronise the
device, and then begin recoding again. This occasionally leaves me with a ride
split into two recordings.

I enjoyed writing this short shell sciprt. It is simple, executable from the
command line and doesn't require me to upload my files to some website.

