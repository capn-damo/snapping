# snapping
Scripts for window snapping

# Based on ideas in a script found at
# http://icculus.org/pipermail/openbox/2013-January/007772.html
#
# Written by damo <damo@bunsenlabs.org> October 2015
#
# The script snaps a window to left or right halves of screen, or top and bottom,
# using X window properties for getting and storing values.
#
# Left, right, top, or bottom screen margins can be specified (negative values allowed);
# Works with dual monitors - windows will snap to edges of monitor they are on;
# Honours user-defined Openbox left and right screen margins;
# Works with decorated and undecorated windows, and windows with no borders;
# Doesn't cover panels at top,bottom, desktop left or desktop right.
#
# REQUIRES: xdotool, wmctrl
#
########################################################################
#
# TODO: Account for _NET_WORKAREA with top/bottom snapping if panel only
# appears on the other monitor.
#
########################################################################
