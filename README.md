# 🎯 Complete ChatGPT Configuration Analysis
*Comprehensive deobfuscation of 3,099 configuration elements*

---

## 📊 Processing Summary

**Total Elements Processed**: 3099
**Elements by Category:**
- Search Optimization: 33 elements
- Experiments: 120 elements
- Feature Flags: 248 elements
- Performance Settings: 30 elements
- System Components: 542 elements
- User Interface: 31 elements
- Authentication: 22 elements
- Connectors: 41 elements
- Model Configurations: 25 elements
- Temporal Settings: 16 elements
- Numerical Mappings: 37 elements
- String Mappings: 511 elements
- Pointer References: 789 elements
**Processing Complete**: True

---

## 🔍 Search Optimization Settings

**enable_source_specific_search_params**: `retrieval_additional_system_prompt`

**The user may have connected sources. If they have, you can assist the user by searching over documents from their connected sources, using the file_search tool. For example, this may include documents from their Google Drive, or files from their Dropbox. The exact sources (if any) will be mentioned to you in a follow-up message.

Use the file_search tool to assist users when their request may be related to information from connected sources, such as questions about their projects, plans, documents, or schedules, BUT ONLY IF IT IS CLEAR THAT the user's query requires it; if ambiguous, and especially if asking about something that is clearly common knowledge, or better answerable from a different tool, DO NOT SEARCH SOURCES. Use the `web` tool instead when the user asks about recent events / fresh information, or asks about news etc. Conversely, if the user's query clearly expects you to reference / read some non-public resource, it is likely that they are expecting you to search connectors.

Note that the file_search tool allows you to search through the connected soures, and interact with the results. However, you do not have the ability to _exhaustively_ list documents from the corpus and you should inform the user you cannot help with such requests. Examples of requests you should refuse are 'What are the names of all my documents?' or 'What are the files that need improvement?'

IMPORTANT: Your answers, when relating to information from connected sources, must be detailed, in multiple sections (with headings) and paragraphs. You MUST use Markdown syntax in these, and include a significant level of detail, covering ALL key facts. However, do not repeat yourself. Remember that you can call file_search more than once before responding to the user if necessary to gather all information.

**Capabilities limitations**:
- You do not have the ability to exhaustively list documents from the corpus.
- You also cannot access to any folders information and you should inform the user you cannot help with folder-level related request. Examples of requests you should refuse are 'What are the names of all my documents?' or 'What are the files that need improvement?' or 'What are the files in folder X?'.
- Also, you cannot directly write the file back to Google Drive.
- For Google Sheets or CSV file analysis: If a user requests analysis of spreadsheet files that were previously retrieved - do NOT simulate the data, either extract the real data fully or ask the users to upload the files directly into the chat to proceed with advanced analysis.
- You cannot monitor file changes in Google Drive or other connectors. Do not offer to do so.**: `enable_dynamic_prompt`

**vocabulary_search_enabled**: `use_coarse_grained_filters_for_vocabulary_search`

**use_coarse_grained_filters_for_vocabulary_search**: `6SWgr0tHm2AcdrsxViTpTw:100.00:1`

**https://persistent.oaistatic.com/deep-research/nux.070152025.mp4**: `posterUrl`

**https://persistent.oaistatic.com/deep-research/nux.070152025.jpg**: `[]`

**The user provided feedback on a previous completion. Use it to generate a new completion. The output should be a standalone response that reflects the feedback without acknowledging it. Do not mention, suggest, or imply that this is a revision, improvement, or result of feedback. Respond in the same language as the original completion, even if the feedback is in another language. Only switch if the feedback explicitly asks you to translate the completion. Here is the feedback:
**: `[]`

**should_show_deep_research_upsell_banner**: `should_show_deep_research_upsell_banner_free`

**should_show_deep_research_upsell_banner_free**: `should_show_codex_upsell_banner`

**enable_indexing**: `backfill_completed`

**enable_local_indexing**: `enable_ux`

**user_context_message_search_tools_default**: `search_tool_holdout_enabled`

**search_tool_holdout_enabled**: `[]`

**use_modapi_in_autocomplete**: `use_memory_in_model_autocomplete`

**use_memory_in_model_autocomplete**: `autocomplete_max_char`

**autocomplete_max_char**: `32`
  *Maximum characters for autocomplete suggestions*

**search_autocomplete_mode**: `BING`
  *Search engine optimization mode*

**autocomplete_min_char**: `autocomplete_mode`

**autocomplete_mode**: `INDEX`

**INDEX**: `num_completions_to_fetch_from_index`

**num_completions_to_fetch_from_index**: `8`
  *Number of pre-computed suggestions to fetch*

**search_in_overflow_for_free_users**: `configuration_menu`

**search**: `picture_v2`

**research**: `use_mixed_suggestions`

**search_team_followups_enabled**: `agent_suggestions`

**search_scoring_dyconfig_name**: `gizmo_search_score_config`
  *Dynamic scoring configuration system*

**gizmo_search_score_config**: `[]`

**starter_prompt_ranking_algorithm**: `homepage_v2`

**autocomplete_qualified_start_date**: `2000-10-11T00:00:00Z`

**enable_new_autocomplete_homepage**: `model_talks_option`

**autocomplete_fetch_interval**: `enable_recommend_prompts`

**prefetchSearch**: `routes/_conversation._index`

**routes/_conversation._index**: `actionData`

---

## 🧪 A/B Testing Experiments (120 total)

### Full Rollout (88 experiments)

🟢 **74LEnvIdaTOsXlJatmPFx2**
  - Allocation: 100.0%
  - Variant: 1

🟢 **3fMwbokU30ECZHyTXDWyJw**
  - Allocation: 100.0%
  - Variant: 1

🟢 **1vGfaAvyQ4VnZ5Y0UnCsbl**
  - Allocation: 100.0%
  - Variant: 5

🟢 **3cQqufsn9EF8iqIPZFNiE8**
  - Allocation: 100.0%
  - Variant: 4

🟢 **bhPM7FsN2H1vnBUrxrg6v**
  - Allocation: 100.0%
  - Variant: 3

🟢 **6VUF6Z1JaUKZF7RS6uSjUu**
  - Allocation: 100.0%
  - Variant: 6

🟢 **5pv2QpbgXNDB0QnBo3LTti**
  - Allocation: 100.0%
  - Variant: 2

🟢 **2MQYHJjfKwcTr14d1bOuVH**
  - Allocation: 100.0%
  - Variant: 2

🟢 **598ORr5O5ZardhhzMhz8k0**
  - Allocation: 100.0%
  - Variant: 15

🟢 **5GxJyyvuXiX6JrRFmDz5TK**
  - Allocation: 100.0%
  - Variant: 2

*... and 78 more full_rollout experiments*

### Disabled (19 experiments)

🔴 **4qrPR4YgnMDXGxt5PaOi2C**
  - Allocation: 0.0%
  - Variant: 1

🔴 **muV45DjtwM1FqEVQdfU48**
  - Allocation: 0.0%
  - Variant: 7

🔴 **4kfyoZAXBVLtFe22ng71gq**
  - Allocation: 0.0%
  - Variant: 2

🔴 **3Pv3bKbjUQIOMSDClknPPU**
  - Allocation: 0.0%
  - Variant: 6

🔴 **2GzNaY2UIV2RYDjl4grJNG**
  - Allocation: 0.0%
  - Variant: 1

🔴 **4cUAiUhaPmuDSuw2J4Wwmn**
  - Allocation: 0.0%
  - Variant: 2

🔴 **11IqDt7xc4mMNiyiSIMy1F**
  - Allocation: 0.0%
  - Variant: 1

🔴 **5YmVfFSujv4W72Pbd8p9fX**
  - Allocation: 0.0%
  - Variant: 4

🔴 **hZcpoVxejOs7BOoqwsNkI**
  - Allocation: 0.0%
  - Variant: 16

🔴 **5OIO2mI7iQiPRReG1jZ4c2**
  - Allocation: 0.0%
  - Variant: 7

*... and 9 more disabled experiments*

### Significant Test (4 experiments)

🟢 **4C2vO0R7mvnCZvl1HDBExp**
  - Allocation: 30.0%
  - Variant: 5

🟢 **3Da3vJtBawdpcHFOEpjzZA**
  - Allocation: 10.0%
  - Variant: 2

🟢 **5BNdlhhVuojDlge4XiI3NF**
  - Allocation: 25.0%
  - Variant: 1

🟢 **6CzIllDlW3zbsFd21Jii1y**
  - Allocation: 20.0%
  - Variant: 2

### Limited Test (5 experiments)

🟢 **BpeZLya4EhDVcnP7pLcih**
  - Allocation: 1.0%
  - Variant: 5

🟢 **3Vq8eWUTWjtrQ9hJ9LdnGO**
  - Allocation: 1.0%
  - Variant: 4

🟢 **4JgLxIsgBJ3ur1hmEZP7Lm**
  - Allocation: 5.0%
  - Variant: 1

🟢 **5JVvgWEQ3oe0bo19yYvY4B**
  - Allocation: 2.0%
  - Variant: 1

🟢 **1nGrz4l6GM0LgZvm0pDCtp**
  - Allocation: 2.0%
  - Variant: 1

### Major Test (4 experiments)

🟢 **505fTupJEquZQo7wgccwMe**
  - Allocation: 99.0%
  - Variant: 14

🟢 **5ZOcA0GpOkaiXc5SAMY0uz**
  - Allocation: 50.0%
  - Variant: 2

🟢 **4DOiTPwuVVuxBaqTj495US**
  - Allocation: 95.0%
  - Variant: 2

🟢 **5EW6yS6u2jgOrZqRd4LygB**
  - Allocation: 99.0%
  - Variant: 5

---

## 🚩 Feature Flags (248 total)

### State Flags (92 flags)

- ✅ `is_device_based`
- ✅ `is_user_in_experiment`
- ✅ `is_experiment_active`
- ✅ `is_in_layer`
- ✅ `is_memory_undo_enabled`
- ✅ `is_starter_prompt_popular`
- ✅ `is_starter_prompt_top_performer`
- ✅ `is_starter_prompt_back_and_forth`
- ✅ `is_starter_prompt_enabled_for_new_users_only`
- ✅ `is_guided_onboarding`
- ✅ `is_static_onboarding`
- ✅ `is_prompt_onboarding`
- ✅ `is_enabled`
- ✅ `is_voice_mode_entry_point_enabled`
- ✅ `is_team_enabled`
*... and 77 more state flags flags*

### Capability Flags (6 flags)

- ✅ `can_see_system_hint_announcement`
- ✅ `has_sidekick_access`
- ✅ `can_download_sidetron`
- ✅ `sign_up_button_has_the_word_free`
- ✅ `has_updates`
- ✅ `has_logged_in_before`

### Behavior Flags (21 flags)

- ✅ `use_freshness_scoring_profile`
- ✅ `use_relevance_lmp`
- ✅ `use_light_weight_scoring_for_slurm_tenants`
- ✅ `should_use_new_ui`
- ✅ `use_broad_rate_limit_language`
- ✅ `use_starter_prompt_help_how_to`
- ✅ `use_dynamic_response`
- ✅ `use_chip_style_citations`
- ✅ `use_plus_rl_during_onboarding`
- ✅ `use_email_otp`
- ✅ `use_new_phone_ui`
- ✅ `use_formatted_national_number`
- ✅ `use_dalle_preview`
- ✅ `use_separate_incorrect_password_error_message`
- ✅ `use_authapi_password_connection_type`
-  and 6 more behavior flags flags*

### Enablement Flags (48 flags)

- ✅ `enable_mclick_urls`
- ✅ `enable_dynamic_prompt`
- ✅ `enable_style_addendum`
- ✅ `enable_query_intent`
- ✅ `enable_mclick_dates`
- ✅ `enable_source_filtering`
- ✅ `enable_mimetype_filtering`
- ✅ `enable_new_onboarding_flow`
- ✅ `enable_o3_mini_retrieval`
- ✅ `enable_reason_by_default`
- ✅ `enable_slash_commands`
- ✅ `enable_rich_text_composer`
- ✅ `enable_arch_updates`
- ✅ `enable_v2_cleanup`
- ✅ `enable_mobile_app_upsell_banner`
- *... and 33 more enablement flags flags*

### Conditional Flags (13 flags)

✅ `should_update_thread_store`
✅ `should_animate_user_message`
✅ `should_animate_composer`
✅ `should_open_cancellation_survey_after_canceling`
✅ `should_offer_paypal_when_eligible`
✅ `should_set_customer_address_country_to_billing_country`
✅ `should_upgrade_pill_persist`
✅ `should_change_model_picker`
✅ `should_simplify_modal`
✅ `should_offer_paypal`
✅ `should_refresh_access_token_error_take_user_to_no_auth`
✅ `should_send_email_on_payment_failure`
✅ `should_overwrite_banner_info`

### Ui Visibility Flags (57 flags)

✅ `should_show_cot_header`
✅ `show_label_on_button`
✅ `onboarding_show_custom_instructions_page`
✅ `onboarding_show_followups`
✅ `show_new_chat_nux`
✅ `show_preview_when_collapsed`
✅ `show_nux`
✅ `should_show_manage_my_subscription_link`
✅ `should_show_cp`
✅ `show_custom_instr_message`
✅ `should_show_purple_sidebar_upsell`
✅ `should_show_return_home_btn`
✅ `show_citations_with_title`
✅ `onboarding_show_other_option`
✅ `show_india_language_upsell_banner`
*... and 42 more ui visibility flags flags*

### Other (11 flags)

✅ `hide_dictation_button`
✅ `hide_new_at_workspace_section`
✅ `hide_section_new_at_workspace`
✅ `login_allow_phone`
✅ `signup_allow_phone`
✅ `in_signup_allow_phone_hold_out`
✅ `hide_gpts_if_none`
✅ `hide_default_gpts`
✅ `allow_receiver_see_user_uploaded_files`
✅ `allow_receiver_see_user_uploaded_files_DO_NOT_ENABLE`
✅ `anon_hide_model_header_dropdown`

---

## ⚡ Performance Settings (30 total)

- **history_results_limit**: `6`

- **local_results_limit**: `2`

- **ca_admin_enabled**: `ca_enabled`

- **max_file_size_mb**: `25`
  *25MB file size limit*

- **max_attempts**: `4`

- **max_bytes**: `31457280`
  *31,457,280 bytes = 30.0MB*

- **voice-status-cache-ttl-ms**: `540000`
  *540000ms = 540.0 seconds*

- **enable-cache-for-gpts**: `enable-cache-for-new-users`

- **enable-cache-for-new-users**: `new-user-within-past-days`

- **enable-cache-if-mic-granted**: `[]`

- **MIN_RETRY_INTERVAL**: `300`

- **MAX_RETRY_INTERVAL**: `5000`

- **RETRY_FACTOR**: `1.5`

- **MAX_RETRY_COUNT**: `12`

- **default_interval**: `3`

- **default_max_polling_duration**: `120`

- **model_slug_intervals**: `{'_1501': 1502, '_1503': 1504}`

- **model_slug_max_polling_durations**: `{'_1507': 1508, '_1509': 1508, '_1503': 1510}`

- **summarizer_chunk_char_limit**: `enable_o3_mini_retrieval`

- **custom_instr_message_timeout_duration**: `1500`

- **attachfile-rate-limit-message-variant**: `title_and_description`

- **attachfile-rate-limit-message-show-icon**: `fully-collapsed-tool-menu`

- **tatortot_contextual_upsell_shown_max_count**: `should_show_tatertot_nux`

- **name_char_limit**: `20`

- **no_auth_soft_rate_limit**: `no_auth_hard_rate_limit`

- **no_auth_hard_rate_limit**: `should_show_no_auth_signup_banner`

- **no_auth_banner_signup_rate_limit**: `composer_text`

- **inference_debounce_ms**: `200`
  *200ms = 0.2 seconds*

- **billing_failure_banner_interval_mins**: `1440`

- **animation_duration**: `700`

---

## 🔧 System Components (542 total)

### Feature Gate (542 items)

#### Trace Id (1 gates)
- `8773623915945316200` (19 digits)

#### Compact Gate (125 gates)
- `16480203` (8 digits)
- `28816792` (8 digits)
- `46455729` (8 digits)
- `51772912` (8 digits)
- `80186230` (8 digits)
- `44045625` (8 digits)
- `108590566` (9 digits)
- `156153730` (9 digits)
- `174366048` (9 digits)
- `212625335` (9 digits)
*... and 115 more compact_gate gates*

#### Standard Gate (416 gates)
- `2711769261` (10 digits)
- `1259585210` (10 digits)
- `1923022511` (10 digits)
- `4180060165` (10 digits)
- `3765213438` (10 digits)
- `3922476776` (10 digits)
- `1457171347` (10 digits)
- `1426009137` (10 digits)
- `1030527215` (10 digits)
- `1032814809` (10 digits)
*... and 406 more standard_gate gates*

---

## 🤖 Model Configurations (25 total)

- **reranker_model**: `ret-rr-skysight-v3`
- **allowed_models**: `[]`
- **gpt_4o**: `5`
- **o1_pro**: `1200`
- **o3_pro**: `600`
- **model**: `gpt-4o`
- **gpt-4o**: `[]`
- **model_talks_first**: `model_talks_first_kind`
- **model_talks_first_kind**: ``
- **model_talks_first_augment_system_prompt**: `is_starter_prompt_enabled_for_new_users_only`
- **override_o3_mini_to_high**: `enable_reason_by_default`
- **dalle**: `file_upload`
- **gpt_discovery_experiment_enabled**: `popular_at_my_workspace_enabled`
- **prefetch-models**: `sidebar-default-close`
- **in_dalle_preview_exp**: `[2098]`
- **chatGPT**: `in_login_web_branding_experiment`
- **show-model-picker**: `[2313]`
- **sahara_model_id_override**: `[]`
- **filter_prompt_by_model**: `headline_option`
- **chatgpt_anon_heading_enabled**: `anon_hide_model_header_dropdown`
- **gpt-4o-mini**: `category_tabs`
- **gpt_pgp_28_d_v2**: `[]`
- **filter_starter_prompt_by_model**: `autocomplete_qualified_start_date`
- **model_talks_option**: `enable_hardcoded_onboarding_prompt`
- **rq:["models",{"IIM":false,"isGizmo":false}]**: `['P', 3092]`

---

## 🔗 Connector Systems (41 total)

✅ **metehan777(gmail).com**
  - Index: 26
  - Status: Enabled

✅ **enabledConnectors**
  - Index: 1111
  - Status: Enabled

✅ **gdrive_action_connector**
  - Index: 1113
  - Status: Enabled

✅ **slurm_dropbox**
  - Index: 1114
  - Status: Enabled

✅ **dropbox_connector**
  - Index: 1115
  - Status: Enabled

✅ **slurm_sharepoint**
  - Index: 1116
  - Status: Enabled

✅ **sharepoint_connector**
  - Index: 1117
  - Status: Enabled

✅ **box_connector**
  - Index: 1119
  - Status: Enabled

✅ **canva_connector**
  - Index: 1121
  - Status: Enabled

✅ **slurm_notion**
  - Index: 1122
  - Status: Enabled

✅ **notion_connector**
  - Index: 1123
  - Status: Enabled

✅ **hubspot_connector**
  - Index: 1124
  - Status: Enabled

✅ **teams_connector**
  - Index: 1125
  - Status: Enabled

✅ **autoConnectors**
  - Index: 1127
  - Status: Enabled

✅ **google_calendar_connector**
  - Index: 1129
  - Status: Enabled

✅ **gmail_connector**
  - Index: 1130
  - Status: Enabled

✅ **google_contacts_connector**
  - Index: 1131
  - Status: Enabled

✅ **connectorConfig**
  - Index: 1132
  - Status: Enabled

✅ **gdrive**
  - Index: 1138
  - Status: Enabled

✅ **github_connector**
  - Index: 1140
  - Status: Enabled

✅ **linear_connector**
  - Index: 1145
  - Status: Enabled

✅ **dropbox**
  - Index: 1151
  - Status: Enabled

✅ **sharepoint**
  - Index: 1155
  - Status: Enabled

✅ **outlook_calendar_connector**
  - Index: 1162
  - Status: Enabled

✅ **outlook calendar**
  - Index: 1165
  - Status: Enabled

✅ **office 365 calendar**
  - Index: 1166
  - Status: Enabled

✅ **o365 calendar**
  - Index: 1167
  - Status: Enabled

✅ **outlook_email_connector**
  - Index: 1168
  - Status: Enabled

✅ **intercom_connector**
  - Index: 1177
  - Status: Enabled

✅ **hubspot**
  - Index: 1183
  - Status: Enabled

✅ **slack_connector**
  - Index: 1187
  - Status: Enabled

✅ **slack**
  - Index: 1190
  - Status: Enabled

✅ **notion**
  - Index: 1193
  - Status: Enabled

✅ **gcal_connector**
  - Index: 1197
  - Status: Enabled

✅ **google calendar**
  - Index: 1200
  - Status: Enabled

✅ **gmail**
  - Index: 1203
  - Status: Enabled

✅ **gdrivePicker**
  - Index: 1372
  - Status: Enabled

✅ **gdriveLink**
  - Index: 1374
  - Status: Enabled

✅ **gdrivePercentage**
  - Index: 1378
  - Status: Enabled

✅ **outlook_calendar**
  - Index: 1561
  - Status: Enabled

✅ **google_calendar**
  - Index: 1562
  - Status: Enabled

---

## 📈 Summary Statistics

- **Total Elements Processed**: 3,099
- **Search Settings**: 33
- **Active Experiments**: 120
- **Feature Flags**: 248
- **System Components**: 542
- **Performance Settings**: 30
- **Model Configurations**: 25
- **Connectors**: 41
