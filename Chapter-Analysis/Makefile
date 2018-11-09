# "all" target is needed for calling make w/ no argument
# we actually use the "default" target in the parent directory makefile
default:
	@make -C .. $@
# wildcard target captures targets in this directory and passes them up to the parent
%:
	@make -C .. $@
