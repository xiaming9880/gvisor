load("defs.bzl", "packetdrill_linux_test", "packetdrill_netstack_test", "packetdrill_test")

package(licenses = ["notice"])

packetdrill_test(
    name = "packetdrill_sanity_test",
    scripts = ["sanity_test.pkt"],
)

packetdrill_test(
    name = "accept_ack_drop_test",
    scripts = ["accept_ack_drop.pkt"],
)

packetdrill_test(
    name = "fin_wait2_timeout_test",
    scripts = ["fin_wait2_timeout.pkt"],
)

packetdrill_linux_test(
    name = "tcp_user_timeout_test_linux_test",
    scripts = ["linux/tcp_user_timeout.pkt"],
)

packetdrill_netstack_test(
    name = "tcp_user_timeout_test_netstack_test",
    scripts = ["netstack/tcp_user_timeout.pkt"],
)

packetdrill_test(
    name = "listen_close_before_handshake_complete_test",
    scripts = ["listen_close_before_handshake_complete.pkt"],
)

packetdrill_test(
    name = "no_rst_to_rst_test",
    scripts = ["no_rst_to_rst.pkt"],
)

packetdrill_test(
    name = "tcp_defer_accept_test",
    scripts = ["tcp_defer_accept.pkt"],
)

packetdrill_test(
    name = "tcp_defer_accept_timeout_test",
    scripts = ["tcp_defer_accept_timeout.pkt"],
)
