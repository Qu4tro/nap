*Snore*

    usage: snore [-h] [--quiet] [--dry-run] [--poll-time] {for,until} ... time

    Sleep tight :)

    positional arguments:
      {for,until}
        for            Sleep for the given time
        until          Sleep until the given time
      time             Time values postfixed by their respective units separated
                       by nothing

    optional arguments:
      -h, --help       show this help message and exit
      --quiet, -q      No output
      --dry-run, -0    Only output
      --poll-time, -p  Instead of sleeping the entire time, checks every second if
                       the given time has arriven.

    Example:
        snore for 1h10m
        snore for 1s1m
        snore for 30s
        snore until 9h23m10s
        snore -q until 14h
        snore -0 until 9h23m10s
