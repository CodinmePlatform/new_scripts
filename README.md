# new_scripts
new scripts for my platform

the script must see like thet:

from my_libery.imports import job
class new_script(job.job):
   def __init__(self):
      pass
   def help(self):
      h = '''
          help string like:
          search(<name>)
          delete(<name>, *<password>) * mine opzionalic
          '''
   def start(self, cmd):
      self.cmd = cmd

name_of_script = new_script()
