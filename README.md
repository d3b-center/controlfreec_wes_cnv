# controlfreec_cnv
Re-develop/redeploy our controlfreec tool to incorporate exome mode
When running exome mode: include bed file and 'Y' for exome flag. Otherwise, it will run WGS 

Current docker:
https://github.com/d3b-center/bixtools/tree/master/controlfreec/11.5

Current use in somatic wes wf:
https://github.com/kids-first/kf-somatic-workflow/tree/mb-add-sans-cnv

Control FreeeC Docs:
http://boevalab.com/FREEC/tutorial.html#EXOME
