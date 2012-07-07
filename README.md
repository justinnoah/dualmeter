dualMeter
=========

A jquery plugin that displays a graphical meter with two metering options. This is specifically useful for showing used, allocated, and total amounts of RAM or disk space, etc. in one meter.

Usage
=====

    $('#myelement').dualMeter(settings);

where settings is something like:

    var settings = {
        'primary':'50',
        'secondary':'22',
    }

Primary and secondary are used as percentages so they will take a value between 0 and 100. For some examples, check out the repo and take a look at examples.html.