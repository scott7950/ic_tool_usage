
CM_DIR  = vcs_covdir.vdb
TEST   ?= test1 

comp:
  vcs –cm line+tgl+fsm+branch+cond –cm_dir $(CM_DIR)

sim:
  simv –cm line+tgl+fsm+branch+cond –cm_dir $(CM_DIR) –cm_name $(TEST)
  
comp1:
	vcs –cm line+cond+fsm –o mysimv

sim1:
  mysimv –cm line+tgl+fsm+branch+cond –cm_dir mysimv.vdb –cm_name $(TEST)
