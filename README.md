# DotaConsole
autoexec.cfg
dota_player_smart_multiunit_cast 1<br>
<br>
<br>
alias "Wdefault" "dota_ability_quickcast 1"<br>
alias cycleW "dota_cycle_selected; Wdefault;"<br>
alias "heroAndUnits1" "cycleW; dota_cycle_prev_selected;"<br>
alias "heroAndUnits2" "cycleW; cycleW; dota_cycle_prev_selected; dota_cycle_prev_selected;"<br>
alias "heroAndUnits3" "cycleW; cycleW; cycleW; dota_cycle_prev_selected; dota_cycle_prev_selected; dota_cycle_prev_selected; "<br>
alias "heroAndUnits4" "cycleW; cycleW; cycleW; cycleW; dota_cycle_prev_selected; dota_cycle_prev_selected; dota_cycle_prev_selected; dota_cycle_prev_selected;"<br>
alias "heroAndUnits5" "cycleW; cycleW; cycleW; cycleW; cycleW; dota_cycle_prev_selected; dota_cycle_prev_selected; dota_cycle_prev_selected; dota_cycle_prev_selected; dota_cycle_prev_selected;"<br>
<br>
alias groupSpellToggle "oneUnit" <br>
alias oneUnit "bind B heroAndUnits1;   alias groupSpellToggle twoUnit" <br>
alias twoUnit "bind B heroAndUnits2;  alias groupSpellToggle threeUnit"<br>
alias threeUnit "bind B heroAndUnits3;  alias groupSpellToggle fourUnit"<br>
alias fourUnit "bind B heroAndUnits4;  alias groupSpellToggle fiveUnit"<br>
alias fiveUnit "bind B heroAndUnits5;  alias groupSpellToggle oneUnit"<br>
<br>
<br>
bind "KP_+" groupSpellToggle<br>
<br>
bind KP_1 "bind B heroAndUnits1; alias groupSpellToggle twoUnit"<br>
bind KP_2 "bind B heroAndUnits2; alias groupSpellToggle threeUnit"<br>
bind KP_3 "bind B heroAndUnits3; alias groupSpellToggle fourUnit"<br>
bind KP_4 "bind B heroAndUnits4; alias groupSpellToggle fiveUnit"<br>
bind KP_5 "bind B heroAndUnits5; alias groupSpellToggle oneUnit"<br>
