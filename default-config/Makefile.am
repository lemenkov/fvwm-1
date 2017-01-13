## Process this file with automake to create Makefile.in

configdir = @FVWM_DATADIR@/default-config
config_DATA = config \
	      .stalonetrayrc \
	      FvwmScript-DateTime \
	      FvwmScript-ConfirmQuit \
	      FvwmScript-ConfirmCopyConfig

EXTRA_DIST  = images \
	      config \
	      .stalonetrayrc \
	      FvwmScript-DateTime \
	      FvwmScript-ConfirmQuit \
	      FvwmScript-ConfirmCopyConfig

uninstall-hook:
	rm -fr $(configdir)
	rm @FVWM_DATADIR@/FvwmScript-*
