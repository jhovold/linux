# SPDX-License-Identifier: GPL-2.0
# Copyright (C) B.A.T.M.A.N. contributors:
#
# Marek Lindner, Simon Wunderlich

obj-$(CONFIG_BATMAN_ADV) += batman-adv.o
batman-adv-y += bat_algo.o
batman-adv-y += bat_iv_ogm.o
batman-adv-$(CONFIG_BATMAN_ADV_BATMAN_V) += bat_v.o
batman-adv-$(CONFIG_BATMAN_ADV_BATMAN_V) += bat_v_elp.o
batman-adv-$(CONFIG_BATMAN_ADV_BATMAN_V) += bat_v_ogm.o
batman-adv-y += bitarray.o
batman-adv-$(CONFIG_BATMAN_ADV_BLA) += bridge_loop_avoidance.o
batman-adv-$(CONFIG_BATMAN_ADV_DAT) += distributed-arp-table.o
batman-adv-y += fragmentation.o
batman-adv-y += gateway_client.o
batman-adv-y += gateway_common.o
batman-adv-y += hard-interface.o
batman-adv-y += hash.o
batman-adv-$(CONFIG_BATMAN_ADV_DEBUG) += log.o
batman-adv-y += main.o
batman-adv-y += mesh-interface.o
batman-adv-$(CONFIG_BATMAN_ADV_MCAST) += multicast.o
batman-adv-$(CONFIG_BATMAN_ADV_MCAST) += multicast_forw.o
batman-adv-y += netlink.o
batman-adv-$(CONFIG_BATMAN_ADV_NC) += network-coding.o
batman-adv-y += originator.o
batman-adv-y += routing.o
batman-adv-y += send.o
batman-adv-$(CONFIG_BATMAN_ADV_TRACING) += trace.o
batman-adv-y += tp_meter.o
batman-adv-y += translation-table.o
batman-adv-y += tvlv.o

CFLAGS_trace.o := -I$(src)
