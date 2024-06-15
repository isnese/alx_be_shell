#!/bin/bash
whoami | tee /dev/tty | wc -c | xargs -I{} echo "[Got]\n\n({} chars long)\n\n[Expected]\n$(whoami)\n\n(5 chars long)"
