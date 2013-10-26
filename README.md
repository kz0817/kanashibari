kanashibari
===========

A utility that suspends and resumes processes. It's major purpose
is to save power consumption by suspending  some processes are working in
background when that are not used such as a web browser.

Hint
----
A useful situation of this program is when the lid of (laptop)
PC is closed/opened.

On ubuntu 13.04, the following setting makes it active.

    # mkdir -p /etc/acpi/local
    # ln -s <kanashibari_path>kanasihibari /etc/acpi/local/lid.sh.pre

On ubuntu 13.10, the following setting makes it active.
    # mkdir -p /etc/acpi/local
    # ln -s <kanashibari_path>/events.lid /etc/acpi/events/lid
    # ln -s <kanashibari_path>/kanshibari /etc/acpi/local/lid.py
