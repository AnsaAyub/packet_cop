# packet_cop
# PacketFilterFirewall

## Overview

    Simulates a basic packet filter firewall for educational purposes.
    Allows users to create rules for filtering network traffic based on IP addresses and ports.
    Provides a graphical user interface for adding rules and testing packets.

## Usage

    Compile and run:
        Compile the PacketFilterFirewall.java file using a Java compiler.
        Execute the compiled class file to start the application.
    Add rules:
        Enter the desired source IP address, destination IP address, source port, and destination port in the corresponding text fields.
        Click the "Add Rule" button to create the rule.
    Test packets:
        Enter the IP addresses and ports of a packet you want to test in the text fields.
        Click the "Test Packet" button to check if it's allowed or blocked based on the rules.
    View results:
        The "resultArea" will display whether the packet is allowed or blocked.

## Key Components

    GUI: The code utilizes Java Swing to create a graphical user interface for user interaction.
    Rule storage: Rules are stored in a List object for efficient rule management.
    Rule matching: The testPacket() method checks each rule against a packet's attributes to determine if it should be allowed or blocked.
    Result display: The GUI provides clear feedback on the outcome of packet tests.

## Notes

    This is a simplified simulation for educational purposes, not a fully functional firewall for real-world security.
    It focuses primarily on IP addresses and ports, while real firewalls often consider additional filtering criteria.
    The provided code does not include the matches() method within the PacketFilterFirewall class, which is essential for rule comparison.

## Author

    Ansa Ayub
