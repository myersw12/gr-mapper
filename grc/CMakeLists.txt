# Copyright 2011 Free Software Foundation, Inc.
#
# This file is part of GNU Radio
#
# GNU Radio is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3, or (at your option)
# any later version.
#
# GNU Radio is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with GNU Radio; see the file COPYING.  If not, write to
# the Free Software Foundation, Inc., 51 Franklin Street,
# Boston, MA 02110-1301, USA.
install(FILES
    mapper_mapper.block.yml
    mapper_demapper.block.yml
    mapper_demapper_soft.block.yml
    mapper_mapper_msg.block.yml
    mapper_demapper_msg.block.yml
    mapper_preamble_insert_bb.block.yml
    mapper_preamble_sync_cc.block.yml
    mapper_preamble_sync_demapper.block.yml
    mapper_preamble_sync_demapper_hard.block.yml
    mapper_preamble_strip.block.yml
    mapper_timeslot_demux.block.yml
    mapper_prbs_source_b.block.yml 
    mapper_prbs_sink_b.block.yml DESTINATION share/gnuradio/grc/blocks
)
