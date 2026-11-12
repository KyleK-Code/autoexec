# autoexec
LAN Setup

//Movement Keys
bind "a" "+left"
bind "d" "+right" 
bind "w" "+forward" 
bind "s" "+back"  
bind "ctrl" "+duck" 
bind "shift" "+sprint" 
bind "mwheeldown" "+jump"
bind "mwheelup" "+jump"

//Unbinds
unbind "alt"
unbind "k"
unbind "p"
unbind "c"
unbind "z"
unbind "i"
unbind "/"
unbind "f1"
unbind "f2"
unbind "f3"
unbind "f4"
unbind "f5"
unbind "f6"
unbind "f7"
unbind "f8"
unbind "f9"
unbind "f10"
unbind "f11"
unbind "f12"

unbind "m"
unbind ","
unbind "."

//Binds
bind "1" "slot1"
bind "2" "slot2"
bind "3" "slot3"
bind "4" "slot4"
bind "5" "slot5"
bind "b" "buymenu"
bind "v" "switchhands"
bind "e" "+use"
bind "f" "+lookatweapon"
bind "g" "drop"
bind "h" "noclip"
bind "l" "+spray_menu"
bind "o" "buy vesthelm; buy m4a1; buy ak47
bind "q" "lastinv"
bind "r" "+reload"
bind "u" "messagemode2"
bind "`" "toggle cl_radar_scale 1 0.3"
bind "ALT" "player_ping"
bind "y" "messagemode"d
bind "=" "toggleconsole"
bind "\" "teammenu"
bind "TAB" "+showscores"
bind "ESCAPE" "cancelselect"
bind "DEL" "mute"
bind "PAUSE" "pause"
bind "mouse4" "+voicerecord"


//Grenade Binds
bind "C" "slot7"
bind "X" "slot8"
bind "Z" "slot10"

//Demo Reviews
bind "downarrow" "demo_gototick -320 relative" // skip back 5 seconds
bind "uparrow" "demo_gototick +320 relative" // skip back 5 seconds
bind "p" demo_togglepause // toggle pause demo

//Warmup Servers
alias d2warmup "connect 23.156.136.146:26640"
alias mirwarmup "connect 104.128.48.8:27015"

//Mouse
sensitivity .88
zoom_sensitivity_ratio 1
hud_showtargetid 1
m_yaw 0.022000
m_pitch 0.022000

//Crosshair
apply_crosshair_code CSGO-T6UMm-6hkiN-pjxWt-sXwkY-yW7VH

//Radar
cl_radar_square_with_scoreboard 0
cl_hud_radar_scale 1.15
cl_radar_scale 0.7
cl_teammate_colors_show 1
cl_radar_rotate 1
cl_radar_scale_alternate 1
cl_hud_radar_background_alpha .3
cl_hud_radar_map_additive 1
cl_radar_always_centered 1

//Viewmodel
viewmodel_fov "68"
viewmodel_offset_x "2.5"
viewmodel_offset_y "0"
viewmodel_offset_z "-1.5"

//Settings
r_fullscreen_gamma "2.2"
rate 1000000
safezonex "0.9"
safezoney "1.0"
cl_allow_animated_avatars "0"
cl_hud_color "4"
cl_use_opens_buy_menu "0"
cl_color "4"
cl_sniper_auto_rezoom 1
cl_showloadout 1
cl_teamcounter_playercount_instead_of_avatars 0
engine_low_latency_sleep_after_client_tick 1
r_show_build_info "0"
fps_max 999
hud_scaling "1.0"
cl_obs_interp_enable 0
con_enable 1 
cl_debounce_zoom 0
cl_prefer_lefthanded 0
cl_silencer_mode 0
cl_force_spec_hud_color_to_team 1
cl_showfps 1
cl_invites_only_mainmenu 1
cl_invites_only_friends 1

//Communication and Mute 
cl_mute_all_but_friends_and_party 0
cl_mute_enemy_team 0
cl_player_ping_mute 1
cl_sanitize_muted_players 1

//Damage Prediction TESTING
cl_predict_body_shot_fx 0
cl_predict_head_shot_fx 0
cl_predict_kill_ragdolls 0

//Background
ui_mainmenu_bkgnd_movie_539CD0B9 cs_office
ui_vanitysetting_team ct
ui_vanitysetting_loadoutslot_ct rifle1

//Sound Settings
snd_deathcamera_volume 0
snd_ducktovolume 0.55
snd_gamevoicevolume 1
snd_gamevolume 1
snd_mapobjective_volume 0
snd_menumusic_volume 0
snd_musicvolume 1
snd_mvp_volume 0
snd_roundaction_volume 0
snd_roundend_volume 0
snd_roundstart_volume 0
snd_steamaudio_reverb_level_db -3
snd_steamaudio_enable_perspective_correction 0
snd_spatialize_lerp 1
snd_tensecondwarning_volume 0.04
snd_toolvolume 1
snd_voipvolume 1
snd_headphone_eq 0
volume 0.01
snd_voipvolume 0.5

//New Grenade Commands
cl_grenadecrosshair_decoy 0
cl_grenadecrosshair_explosive 0
cl_grenadecrosshair_fire 0
cl_grenadecrosshair_flash 0
cl_grenadecrosshair_keepusercrosshair 1
cl_grenadecrosshair_smoke 1
cl_grenadecrosshairdelay_smoke 0.5

//Telemetry
cl_hud_telemetry_frametime_show 2
cl_hud_telemetry_net_misdelivery_show 0
cl_hud_telemetry_ping_show 0

clear

