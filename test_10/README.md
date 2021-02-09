

Tests collection integration




Prereqs:


    ansible-galaxy collection install benthomasson.desired_state --force

Using monitor:

    ansible-state monitor empty_state3.yml

    ansible-state update-desired-state host_state.yml
    ansible-state update-desired-state full_state.yml


OR in one step using from-to:

    ansible-state from empty_state3.yml to full_state.yml
