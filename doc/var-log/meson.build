# SPDX-License-Identifier: LGPL-2.1+
#
# Copyright © 2017 Zbigniew Jędrzejewski-Szmek

file = configure_file(
        input : 'README.in',
        output : 'README',
        configuration : substs)

if conf.get('HAVE_SYSV_COMPAT') == 1
        install_data(file,
                     install_dir : varlogdir)
endif
