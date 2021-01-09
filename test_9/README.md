Works with v3 and network resource modules

Adds operational validation



    ansible-state monitor empty_state.yml rules.yml --inventory inventory.yml --verbose --stream wss://192.168.86.212:8888/ws2

    ansible-state monitor empty_state2.yml --verbose --stream wss://192.168.86.212:8888/ws2


    ansible-state update-desired-state host_state.yml

    ansible-state update-desired-state full_state.yml


    ansible-galaxy collection install benthomasson.desired_state
    ansible-state monitor empty_state3.yml
