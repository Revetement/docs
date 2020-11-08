### URL
`https://s3.cn-north-1.amazonaws.com.cn/twa-game-data.arena.neshgameservers.com/game_config/{GAME_CONFIG}`

### METHOD
`GET`

### Sample request
`https://s3.cn-north-1.amazonaws.com.cn/twa-game-data.arena.neshgameservers.com/game_config/game_config.63F980D03976EE8C9D69D406691756CB.json`

### Sample response

```json
{
  "acceptable_currencies_from_hub": [
    {
      "key": "gold_cents",
      "label": "Gold cents"
    },
    {
      "key": "silver_cents",
      "label": "Silver cents"
    },
    {
      "key": "free_xp_cents",
      "label": "Free XP cents"
    },
    {
      "key": "premium_one_minute",
      "label": "Premium minutes"
    }
  ],
  "additional_alliance_reward_scaling_factor": 3,
  "arena_commanders": {
    "find_items_in": "commander_results"
  },
  "arena_unit_trees": {
    "find_items_in": "unit_results"
  },
  "base_battle_currencies": [
    {
      "currency": "battle_points_cents",
      "table": "arena_currencies"
    }
  ],
  "battle_points_cents": {
    "achievement_type_to_value": "points",
    "add_details_to_stat_record": "add",
    "combine_battle_totals": "add",
    "combine_profile_stat_record": "add",
    "combine_reward_stat_record": "add",
    "default": 0,
    "get_totals_for_battle_and_collate_rewards_impl": "add",
    "profile_stat_record": "present",
    "reward_stat_record": "present",
    "totals": "present",
    "totals_battle": "present"
  },
  "battle_tier_history": {
    "default": {},
    "profile_stat_record": "present"
  },
  "capture_locations": "vic_capture",
  "commander_results": {
    "default": {},
    "totals": "present"
  },
  "commander_unit_results": {
    "default": {},
    "totals": "present"
  },
  "commander_xp_cents": {
    "can_generate_extra_trigger_events_on_add": true
  },
  "damage": {
    "achievement_type_to_value": "damage",
    "caprofile_profile": "present",
    "combine_battle_totals": "add",
    "default": 0,
    "totals": "present",
    "totals_battle": "present"
  },
  "eagles": {
    "caprofile_profile": "present",
    "default": {}
  },
  "faction_results": {
    "default": {},
    "totals": "present"
  },
  "fix_currencies_to_zero": [
    "silver_cents"
  ],
  "free_xp_cents": {
    "achievement_type_to_value": "free_xp",
    "add_details_to_stat_record": "add",
    "battle_tier_record": "present",
    "can_generate_extra_trigger_events_on_add": true,
    "combine_battle_totals": "add",
    "combine_profile_stat_record": "add",
    "combine_reward_stat_record": "add",
    "default": 0,
    "get_totals_for_battle_and_collate_rewards_impl": "add",
    "profile_stat_record": "present",
    "reward_stat_record": "present",
    "totals": "present",
    "totals_battle": "present"
  },
  "friendly_fire_event_name": "hit_friendly",
  "game": "arena",
  "game_client_config": {
    "battle_points_config": {
      "*": {
        "battle_points_multipliers": [
          {
            "category": "hit_block_missile",
            "value": 100
          },
          {
            "category": "capturing_completed",
            "value": 10000
          },
          {
            "category": "hit_evade",
            "value": 34
          },
          {
            "category": "morale_rout",
            "value": 15710
          },
          {
            "category": "spotting_discovery",
            "value": 5000
          },
          {
            "category": "hit_damage",
            "value": 41666
          },
          {
            "category": "hit_kill",
            "value": 10247
          },
          {
            "category": "hit_block_armour",
            "value": 38
          },
          {
            "category": "capturing_counter",
            "value": 6.666667
          },
          {
            "category": "capturing_capture",
            "value": 6.666667
          },
          {
            "category": "morale_buff",
            "value": 100
          },
          {
            "category": "spotting_assisted_damage",
            "value": 0.86
          }
        ],
        "misc_multipliers": {
          "afk_reward_cap": 0.8
        },
        "participation_points_brackets": [
          {
            "points_for_bracket": 450,
            "start_seconds": 0
          },
          {
            "points_for_bracket": 600,
            "start_seconds": 300
          },
          {
            "points_for_bracket": 850,
            "start_seconds": 600
          },
          {
            "points_for_bracket": 1000,
            "start_seconds": 900
          }
        ],
        "stat_buff_rewards": [
          {
            "points_per_percent_buff": 1.4,
            "points_per_percent_debuff": 1.4,
            "stat_key": "stat_charge_bonus"
          },
          {
            "points_per_percent_buff": 1.4,
            "points_per_percent_debuff": 1.4,
            "stat_key": "stat_melee_attack"
          },
          {
            "points_per_percent_buff": 1.54,
            "points_per_percent_debuff": 1.54,
            "stat_key": "stat_melee_damage_base"
          },
          {
            "points_per_percent_buff": 1.4,
            "points_per_percent_debuff": 1.4,
            "stat_key": "stat_melee_defence"
          },
          {
            "points_per_percent_buff": 0.084,
            "points_per_percent_debuff": 0.084,
            "stat_key": "stat_missile_block_chance"
          },
          {
            "points_per_percent_buff": 0,
            "points_per_percent_debuff": 0,
            "stat_key": "scalar_charge_deflect"
          },
          {
            "points_per_percent_buff": 0,
            "points_per_percent_debuff": 0,
            "stat_key": "scalar_charge_impact"
          },
          {
            "points_per_percent_buff": 0,
            "points_per_percent_debuff": 0,
            "stat_key": "scalar_missile_damage_ap"
          },
          {
            "points_per_percent_buff": 0,
            "points_per_percent_debuff": 0,
            "stat_key": "scalar_missile_damage_base"
          },
          {
            "points_per_percent_buff": 0,
            "points_per_percent_debuff": 0,
            "stat_key": "scalar_missile_dispersion"
          },
          {
            "points_per_percent_buff": 0,
            "points_per_percent_debuff": 0,
            "stat_key": "scalar_reload_time_modifier"
          },
          {
            "points_per_percent_buff": 0,
            "points_per_percent_debuff": 0,
            "stat_key": "scalar_weapon_range"
          },
          {
            "points_per_percent_buff": 0,
            "points_per_percent_debuff": 0,
            "stat_key": "stat_armour"
          },
          {
            "points_per_percent_buff": 0,
            "points_per_percent_debuff": 0,
            "stat_key": "stat_melee_damage_ap"
          }
        ],
        "unit_type_reward_modifiers": [
          {
            "mult_received_damage": 2,
            "mult_received_kill": 0.3,
            "unit_type": "war_elephant"
          }
        ]
      }
    },
    "notification_missions_config": [
      "spec_mission_tech_alpha"
    ]
  },
  "game_server_config": {},
  "gold_cents": {
    "can_generate_extra_trigger_events_on_add": true
  },
  "item_lock_prefix": "commander_lock_",
  "kill_or_rout": "vic_rout",
  "kills": {
    "achievement_type_to_value": "kills",
    "add_details_to_stat_record": "add",
    "battle_tier_record": "present",
    "combine_battle_totals": "add",
    "combine_profile_stat_record": "add",
    "default": 0,
    "profile_stat_record": "present",
    "totals": "present",
    "totals_battle": "present"
  },
  "max_eagles": {
    "caprofile_profile": "present",
    "default": [
      {}
    ]
  },
  "max_kills": {
    "add_details_to_stat_record": "max",
    "add_details_to_stat_record_substitute": "kills",
    "combine_profile_stat_record": "max",
    "default": 0,
    "profile_stat_record": "present"
  },
  "max_points_cents": {
    "add_details_to_stat_record": "max",
    "add_details_to_stat_record_substitute": "battle_points_cents",
    "combine_profile_stat_record": "max",
    "default": 0,
    "profile_stat_record": "present",
    "totals_battle": "present"
  },
  "max_unit_xp_cents": {
    "add_details_to_stat_record": "max",
    "add_details_to_stat_record_substitute": "unit_xp_cents",
    "combine_profile_stat_record": "max",
    "default": 0,
    "profile_stat_record": "present"
  },
  "mmr_settings": {
    "10": {
      "mmr_points_favorite_alliance_lost": -26,
      "mmr_points_favorite_alliance_won": 24,
      "mmr_points_nonfavorite_alliance_lost": -24,
      "mmr_points_nonfavorite_alliance_won": 26
    },
    "allowed_on_tiers": [
      10
    ]
  },
  "mmr_t10": {
    "caprofile_profile": "present",
    "default": 1200
  },
  "mp_insufficient_human_players": "invalid",
  "player_level_cents": {
    "can_generate_extra_trigger_events_on_add": true
  },
  "player_level_xp_settings": {
    "player_level_xp_baseline": 21000,
    "player_level_xp_scoreboard_position_penalty": 500,
    "player_level_xp_victory_bonus": 2500
  },
  "premium_currencies_that_must_be_saved": [
    "gold_cents"
  ],
  "primary_key": "commander_key",
  "primary_unit_table": "arena_commanders",
  "reported_currencies": [
    "gold_cents",
    "silver_cents",
    "free_xp_cents"
  ],
  "rewards_to_scale": [
    "gold_cents",
    "silver_cents",
    "free_xp_cents",
    "commander_xp_cents",
    "unit_xp_cents"
  ],
  "scale_additional_bonuses": [
    "player_level_cents",
    "commander_xp_cents"
  ],
  "secondary_key": "unit_key",
  "secondary_unit_table": "arena_unit_trees",
  "service_module_config": {
    "camm": {
      "matchmaker": {
        "*": {
          "ai_disallowed_roles": [
            "artillery",
            "heavy_artillery",
            "archer_cavalry",
            "javelin_cavalry",
            "light_artillery",
            "placeholder",
            "war_dog",
            "war_elephant"
          ],
          "allow_tiers_below_min": true,
          "battle_ranking_weight": 0,
          "commander_tier_multiplier": 0,
          "genetic_accepted_quality": 50,
          "ideal_matches_per_bucket_division": 1,
          "ideal_matchmaking_team_size": 10,
          "max_party_size": 4,
          "max_tier": 10,
          "maximum_party_ratio": 1,
          "min_tier": 1,
          "mmr_weight": 5,
          "number_of_ai_teams": 0,
          "party_weight": 400,
          "ping_weight": 50,
          "player_tier_weight": 200,
          "prevent_matchmaking_on_triggers": [],
          "squad_diversity_weight": 40,
          "squad_role_weight": 50,
          "starting_ideal_queue_size": 300,
          "team_size_multiplier": 2,
          "team_strength_weight": 6000,
          "tier_band_recent_battle_history_multiplier": 0.5,
          "tier_bands": [
            {
              "from": 1,
              "suffix": "all",
              "to": 10
            }
          ],
          "unit_equipment_multiplier": 0
        },
        "pve": {
          "genetic_accepted_quality": 30,
          "max_tier": 10,
          "min_tier": 1,
          "number_of_ai_teams": 1,
          "starting_ideal_queue_size": 10,
          "team_size_multiplier": 1,
          "tier_bands": [
            {
              "from": 1,
              "suffix": "a",
              "to": 3
            },
            {
              "from": 3,
              "suffix": "b",
              "to": 4
            },
            {
              "from": 4,
              "suffix": "c",
              "to": 5
            },
            {
              "from": 5,
              "suffix": "d",
              "to": 7
            },
            {
              "from": 7,
              "suffix": "e",
              "to": 10
            }
          ]
        },
        "pvp": {
          "max_tier": 10,
          "min_tier": 3,
          "tier_bands": [
            {
              "from": 1,
              "suffix": "a",
              "to": 4
            },
            {
              "from": 4,
              "suffix": "b",
              "to": 5
            },
            {
              "from": 5,
              "suffix": "c",
              "to": 7
            },
            {
              "from": 7,
              "suffix": "d",
              "to": 10
            }
          ]
        }
      }
    },
    "camuc": {
      "enable_presence_room": true,
      "lobbies": {
        "language_map": [
          {
            "from_language": "*",
            "to_lobby": "en"
          },
          {
            "from_language": "ru",
            "to_lobby": "ru"
          },
          {
            "from_language": "pl",
            "to_lobby": "ru"
          },
          {
            "from_language": "cz",
            "to_lobby": "ru"
          },
          {
            "from_language": "cs",
            "to_lobby": "ru"
          },
          {
            "from_language": "ja",
            "to_lobby": "ja"
          },
          {
            "from_language": "ko",
            "to_lobby": "ko"
          },
          {
            "from_language": "zh",
            "to_lobby": "zh"
          }
        ],
        "room_max": 1024,
        "room_type": "mass"
      },
      "presence_routing": "nobody",
      "rooms": {
        "maximum_member_count": 250,
        "merge_lower_limit": 45,
        "merge_protection_interval": 1800000,
        "transient_room_leave_delay": 900000
      }
    },
    "general": {
      "currency_item_type": "arena_currencies",
      "game_mode_settings": {
        "*": {
          "custom_game_mode": false,
          "record_recent_battle_history": false,
          "use_eagles": false
        },
        "custom": {
          "custom_game_mode": true
        },
        "pve": {
          "record_recent_battle_history": true
        },
        "pvp": {
          "record_recent_battle_history": true
        }
      }
    }
  },
  "silver_cents": {
    "achievement_type_to_value": "silver",
    "add_details_to_stat_record": "add",
    "can_generate_extra_trigger_events_on_add": true,
    "combine_battle_totals": "add",
    "combine_profile_stat_record": "add",
    "combine_reward_stat_record": "add",
    "default": 0,
    "get_totals_for_battle_and_collate_rewards_impl": "add",
    "profile_stat_record": "present",
    "reward_stat_record": "present",
    "totals": "present",
    "totals_battle": "present"
  },
  "squad_size": 3,
  "stats_keys_generic": [
    "kills",
    "free_xp_cents",
    "silver_cents",
    "unit_xp_cents",
    "battle_points_cents",
    "damage"
  ],
  "timeout": "vic_points",
  "titles": {
    "lookup_table": "arena_titles"
  },
  "unit_equipment_table": "arena_unit_equipments",
  "unit_results": {
    "default": {},
    "totals": "present"
  },
  "unit_table": "arena_unit_trees",
  "unit_xp_cents": {
    "achievement_type_to_value": "unit_xp",
    "add_details_to_stat_record": "add",
    "can_generate_extra_trigger_events_on_add": true,
    "combine_battle_totals": "add",
    "combine_profile_stat_record": "add",
    "combine_reward_stat_record": "add",
    "default": 0,
    "get_totals_for_battle_and_collate_rewards_impl": "add",
    "profile_stat_record": "present",
    "reward_stat_record": "present",
    "totals": "present",
    "totals_battle": "present"
  }
}
```
