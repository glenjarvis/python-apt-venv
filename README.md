

When trying to install package inside of Venv
=============================================

    default:     ERROR: Command errored out with exit status 1:
    default:      command: /vagrant/venv/bin/python2 -c 'import sys, setuptools, tokenize; sys.argv[0] = '"'"'/tmp/pip-req-build-CVYOcN/setup.py'"'"'; __file__='"'"'/tmp/pip-req-build-CVYOcN/setup.py'"'"';f=getattr(tokenize, '"'"'open'"'"', open)(__file__);code=f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' egg_info --egg-base /tmp/pip-pip-egg-info-eSQMT3
    default:          cwd: /tmp/pip-req-build-CVYOcN/
    default:     Complete output (5 lines):
    default:     Traceback (most recent call last):
    default:       File "<string>", line 1, in <module>
    default:       File "/tmp/pip-req-build-CVYOcN/setup.py", line 6, in <module>
    default:         from DistUtilsExtra.command import *
    default:     ImportError: No module named DistUtilsExtra.command
    default:     ----------------------------------------
    default: ERROR: Command errored out with exit status 1: python setup.py egg_info Check the logs for full command output.
The SSH command responded with a non-zero exit status. Vagrant
assumes that this means the command failed. The output for this command
should be in the log above. Please read the output to determine what
went wrong.
