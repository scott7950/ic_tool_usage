
CM_DIR  = vcs_covdir.vdb
TEST   ?= test1 

comp:
  vcs –cm line+tgl+fsm+branch+cond –cm_dir $(CM_DIR)

sim:
  simv –cm line+tgl+fsm+branch+cond –cm_dir $(CM_DIR) –cm_name $(TEST)
