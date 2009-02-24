man8_MANS = sjconf-sl2d.man
DISTCLEANFILES = sjconf-sl2d.man
EXTRA_DIST = sjconf-sl2d.t2t

SUFFIXES = .t2t

.t2t.man:
	txt2tags -o $@ $<
