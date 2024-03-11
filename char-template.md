---
aliases: "<% tp.file.title.split(" - ")[1] %>"
---
# [[<% tp.file.title %>|<% tp.file.title.split(" - ")[1] %>]]
>[!toc]- TOC
>```toc
>```
# View
>[!cols | 31 + notl  + ncborder + noborder]
>>[!notecol] 
>>### [[<% tp.file.title %>#<% tp.file.title.split(" - ")[1] %> profile|<% tp.file.title.split(" - ")[1] %> profile]]
>> #### Summary about `=this.character`
>>```dataview
TABLE WITHOUT ID L.text as Summary
FROM "08 Writing"
WHERE file.link = this.file.link
FLATTEN file.lists as L 
WHERE contains(meta(L.section).subpath, "Summary")
>>```
>>
>>## Questions
>>>[!note | scroll]- [[<% tp.file.title %>#Basic|Basic]] ---------- :luc_arrow_down_circle:
>>>![[<% tp.file.title %>#Basic]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Goals|Goals]] ---------- :luc_arrow_down_circle:
>>>![[<% tp.file.title %>#Goals]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Relationships and conflicts|Relationships and conflicts]] ---------- :luc_arrow_down_circle:
>>>![[<% tp.file.title %>#Relationships and conflicts]]
>>
>>## Profile
>>>[!note | scroll]- [[<% tp.file.title %>#Basic info|Basic info]] ---------- :luc_arrow_down_circle:
>>>![[<% tp.file.title %>#Basic Info]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Classifications|Classifications]] ---------- :luc_arrow_down_circle:
>>>![[<% tp.file.title %>#Classifications]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Physical appearance|Physical appearance]] ----------  :luc_arrow_down_circle:
>>>![[<% tp.file.title %>#Physical appearance]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Stats|Stats]] ---------- :luc_arrow_down_circle:
>>>![[<% tp.file.title %>#Stats]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Attributes|Attributes]] ---------- :luc_arrow_down_circle:
>>>![[<% tp.file.title %>#Attributes]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Character personalities|Personality]] ---------- :luc_arrow_down_circle:
>>>![[<% tp.file.title %>#Character personalities]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Character health|Health]] ---------- :luc_arrow_down_circle: 
>>>![[<% tp.file.title %>#Character health]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Character careers|Careers]] ---------- :luc_arrow_down_circle: 
>>>![[<% tp.file.title %>#Character careers]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Character preferences|preferences]] ---------- :luc_arrow_down_circle: 
>>>![[<% tp.file.title %>#Character preferences]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Relationships|Relationships]] ---------- :luc_arrow_down_circle: 
>>>![[<% tp.file.title %>#Relationships]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Character life stages|Life Stages]] ---------- :luc_arrow_down_circle: 
>>>![[<% tp.file.title %>#Character life stages]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Character perspectives|Perspectives]] ---------- :luc_arrow_down_circle: 
>>>![[<% tp.file.title %>#Character perspectives]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Character background|Background]] ---------- :luc_arrow_down_circle: 
>>>![[<% tp.file.title %>#Character background]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Character developments|Developments]] ---------- :luc_arrow_down_circle: 
>>>![[<% tp.file.title %>#Character developments]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Society|Society]] ---------- :luc_arrow_down_circle:
>>>![[<% tp.file.title %>#Society]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Activities|Activities]] ---------- :luc_arrow_down_circle:
>>>![[<% tp.file.title %>#Activities]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#History|History]] ---------- :luc_arrow_down_circle:
>>>![[<% tp.file.title %>#History]]
>>
>>>[!note | scroll]- [[<% tp.file.title %>#Related info|Related info]] ---------- :luc_arrow_down_circle:
>>>![[<% tp.file.title %>#Related info]]
>
>>[!notecol]
>> ```dataviewjs
dv.span(dv.current().cover)
>>```
>>
>>>[!note | scroll30em h4-cbx] Info
>>>```dataviewjs
dv.view("01 Meta/01.03 Scripts/writing_character/profile")
>>>```

# Summary
- ⭐ one summary line write here
- ⭐ another summary line write here

# The questions
## Basic
- personality type - Enneagram
- personality type - MBTI
- distinctive skills/abilities
- what is their greatest fear?
- what is their misbelief about the world?
- what happened in this character's past to make them believe this lie?
- what do they most often criticize other for?
- how do they respond to emotional pain?
- top three things he/she values most in life?
- is there an object he/she can't bear to part with and why?
- describe a typical outfit for him/her from top to bottom
- what is his/her method of manipulation?
## Goals
- how is your character dissatisfied with their life?
- what does your character believe will bring them true happiness or contentment?
- what definitive step could they take to turn their dream into reality?
- how was their fear kept them from taking this action already?
- how does your protagonist feel they can accomplish their goal while still steering clear of the thing they are afraid of?
## Relationships and conflicts
- in a few words, describe the MC's relationship with this other character
- what are some points of conflict in their relationship?
- what do they agree on? what do they disagree on?
- do they keep any secrets from each other? if so, what and why?
- how did they meet and how long have they known each other?
- how will their relationship change over the course of the story?


# [[<% tp.file.title %>|<% tp.file.title.split(" - ")[1] %> profile]]
## Basic info
### character - official name
 - character_official_name:: [[<% tp.file.title %>|<% tp.file.title.split(" - ")[1] %>]]
### character - official name meaning
 - character_official_name_meaning:: 
### character - official name pronunciation
- character_official_name_pronunciation:: 
### character - alias name
 - character_alias_name:: 
### character - alias name meaning
- character_alias_name_meaning::
### character - alias name pronunciation
- character_alias_name_pronunciation:: 
### character - name backstory
 - character_name_backstory:: 

## Classifications
### character - creature
- character_creature::
### character - role
 - character_role:: 
### character - gender
 - character_gender:: 
### character - race
- character_race:: 
### character - people
- character_people:: 
### character - birthday
 - character_birthday:: 
### character - deathday
 - character_deathday:: 
### character - birth significance
 - character_birth_significance:: 
### character - astrological sign
 - character_astrological_sign:: 
### character - nationality
 - character_nationality:: 
### character - ethnicity
 - character_ethnicity:: 
### character - language
 - character_language:: 
### character - voice
 - character_voice:: 
### character - sexuality
 - character_sexuality:: 

## Physical appearance
### character - general appearance
 - character_general_appearance:: 
### character - actual age
 - character_actual_age:: 
### character - apparent age
 - character_apparent_age::
### character - lifespan
 - character_lifespan:: 
### character - face 
 - character_face:: 
### character - eye
- character_eye:: 
### character - eye color
 - character_eye_color:: 
### character - hair
- character_hair:: 
### character - hair color
 - character_hair_color:: 
### character - size
 - character_size:: 
### character - weight
 - character_weight:: 
### character - height
 - character_height:: 
### character - build
 - character_build:: 
### character - skin
 - character_skin:: 
### character - skin color
 - character_skin_color:: 
### character - fur
 - character_fur:: 
### character - fur color
 - character_fur_color:: 
### character - body mark
 - character_body_mark:: 
### character - distinguishing feature
 - character_distinguishing_feature:: 
### character - limitation
 - character_limitation:: 
### character - other feature
 - character_other_feature::
### character - speech
 - character_speech:: 
### character - fashion
 - character_fashion:: 
### character - posture
 - character_posture:: 
### character - birthmark
 - character_birthmark:: 
### character - dominant hand
 - character_dominant_hand:: 
### character - locomotion
- character_locomotion:: 
### character - persona
- character_persona::


## Stats
### character - health point
- character_health_point:: 
### character - magic point
- character_magic_point:: 
### character - skill
- character_skill::
### character - strength
- character_strength::
### character - weakness
- character_weakness::
### character - dexterity
- character_dexterity::
### character - constitution
- character_constitution::
### character - agility
 - character_agility:: 
### character - vitality
 - character_vitality:: 
### character - wisdom
- character_wisdom::
### character - intelligence
- character_intelligence::
### character - charisma
- character_charisma::
### character - spirit
 - character_spirit:: 
### character - special ability
 - character_special_ability:: 
### character - special ability limitation
 - character_special_limitation:: 
### character - special ability power source
 - character_special_ability_power_source:: 
### character - attack
- character_attack::
### character - special attack
- character_special_attack::
### character - attack success rate
- character_attack_success_rate:: 
### character - attack failure rate
- character_attack_failure_rate:: 
### character - speed
- character_speed::
### character - defense
- character_defense::
### character - damage
- character_damage::


## Attributes
### character - temperament
- character_temperament::

### character - ability
- character_ability::

### character - armor class
- character_armor_class::

### character - natural weapon
- character_natural_weapon::

### character - weapon
- character_weapon::

### character - ranking
- judge, juror, manor, 
- character_speed:: 

### character - tool
- character_tool:: 

### character - ability
- character_ability:: 

### character - magic
- character_magic:: 

### character - power
- character_power:: 

### character - power source   
- character_power_source:: 

### character - value
- character_value:: 

### character - class
- legendary, myth, god, rare, artifact, etc.
- character_class:: 

### character - initial level
- character_initial_level:: 

### character - max level
- character_max_level:: 

### character - combat type
- melee, 
- character_combat_type::

### character - combat range
- character_combat_range::

### character - wielding
- character_wielding::

### character - limitation
- character_limitation:: 

### character - restriction
- character_restriction:: 

### character - domain
- [arcana domain](https://forgottenrealms.fandom.com/wiki/Arcana_domain), [light domain](https://forgottenrealms.fandom.com/wiki/Light_domain)
- character_domain:: 


## Character personalities
### character - personality type
 - character_personality_type::  
### character - temperament
 - character_temperament:: 
### character - greatest fear
 - character_greatest_fear:: 
### character - event that would cause turmoil
 - character_event_that_would_cause_turmoil:: 
### character - at ease when
 - character_at_ease_when:: 
### character - priority
 - character_priority:: 
### character - philosophy
 - character_philosophy:: 
### character - source of strength
 - character_source_of_strength:: 
### character - source of weakness
 - character_source_of_weakness:: 
### character - soft spot
 - character_soft_spots:: 
### character - struggles
 - character_struggles:: 
### character - goal
 - character_goal:: 
### character - motivation
 - character_motivation:: 
### character - talent
 - character_talent:: 
### character - reaction to crisis
 - character_reaction_to_crisis:: 
### character - reaction to change
 - character_reaction_to_change:: 
### character - common problem
 - character_common_problem:: 
### character - trail
 - character_trail:: 
### character - attitude
 - character_attitude:: 
### character - mood
 - character_mood:: 
### character - flaw
 - character_flaw:: 
### character - good habit
 - character_good_habit::  
### character - bad habit
 - character_bad_habit::
### character - pet peeve 
 - character_pet_peev:: 
### character - favourite
 - character_favourite:: 
### character - sin
 - character_sin:: 

## Character health
### character - energy level
 - character_energy_level::  
### character - memory level
 - character_memory_level:: 
### character - disability
 - character_disability::  
### character - phobia
 - character_phobia::  
### character - addiction
 - character_addiction:: 
### character - aptitude
 - character_general_aptitude::  
### character - mental strength
 - character_mental_strength::  
### character - mental weakness
 - character_mental_weakness::  
### character - physical strength
 - character_physical_strength::  
### character - physical weakness
 - character_physical_weakness::  
### character - past illness
 - character_past_illness:: 
### character - surgery
 - character_surgery::  
### character - accident
 - character_accident::  
### character - stability
 - character_stability:: 
### character - allergy
 - character_allergy::  

## Character careers
### character - first job
 - character_first_job::  
### character - current job
 - character_current_job::
### character - past job  
 - character_past_job::  
### character - profession
 - character_profession::  
### character - current organization
 - character_current_organization::  
### character - past organization
 - character_past_organization::  
### character - work ethic
 - character_work_ethic::  

## Character preferences
### character - fav color
 - character_fav_color::  
### character - fav diet
 - character_fav_diet::  
### character - fav music
 - character_fav_music::  
### character - fav food
 - character_fav_food::  
### character - fav literature
 - character_fav_literature::  
### character - fav expression
 - character_fav_expression::  
### character - fav curse
 - character_fav_curse::  
### character - fav entertainment
 - character_fav_entertainment::  
### character - fav quote
 - character_fav_quote::  
### character - fav transportation
 - character_fav_transportation::  
### character - fav drink
 - character_fav_drink::  
### character - fav place
 - character_fav_place::  
### character - fav activity
 - character_fav_activity::  
### character - fav other
 - character_fav_others:: 
### character - happy when
 - character_happy_when::  
### character - sad when
 - character_sad_when::  
### character - hobby
 - character_hobby::  
### character - fav animal
 - character_fav_animal::  
### character - interest
 - character_interest::  

## Relationships
### character - ancestor
 - character_ancestor::
### character - descendant
 - character_descendant::  
### character - parent
 - character_parent:: 
### character - extended family
 - character_extended_family:: 
### character - best friend
 - character_best_friend:: 
### character - friend
 - character_friend:: 
### character - foe
- character_foe::
### character - sibbling
 - character_sibbling:: 
### character - offspring
 - character_offspring:: 
### character - pet
 - character_pet:: 
### character - nature
 - character_nature:: 
### character - best ally
 - character_best_ally:: 
### character - ally
 - character_ally:: 
### character - worst enemy
 - character_worst_enemy:: 
### character - other enemy
 - character_enemy:: 
### character - current partner
 - character_current_partner:: 
### character - ex partner
 - character_ex_partner:: 
### character - first love
 - character_first_love:: 
### character - aspiring love
 - character_aspiring_love:: 
### character - soul mate
 - character_soul_mate:: 

## Character life stages 
### character - significant event
 - character_significant_event::  
### character - childhood
 - character_childhood::  
### character - adolescence
 - character_adolescence::  
### character - young adult
 - character_young_adult::  
### character - adult
 - character_adult::  
### character - coming of age
 - character_coming_of_age::  
### character - significant experience
 - character_significant_experience::  
### character - throughout life
 - character_change_throughout_life::  
### character - major regret
 - character_major_regret::  
### character - life lesson
 - character_life_lesson:: 

## Character perspectives
### character - religion
 - character_religion:: 
### character - upbringing
 - character_upbringing:: 
### character - core value
 - character_core_value:: 
### character - moral
 - character_moral:: 

## Character background
### character - main residence
 - character_main_residence:: 
### character - other residence
 - character_other_residence:: 
### character - original land
 - character_original_land:: 
### character - habitat
 - character_habitat:: 
### character - lifespan
 - character_lifespan:: 
### character - raised in
 - character_raised_in:: 
### character - education
 - character_education:: 



## Character developments
### character - milestone
 - character_milestone:: 
### character - achievement
 - character_achievement:: 
### character - failure
 - character_failure:: 
### character - lifestyle
 - character_lifestyle:: 
### character - attire
 - character_attire:: 
### character - culture
 - character_culture:: 
### character - main goal
 - charl_main_goal:: 
### character - minor goal
 - character_minor_goal:: 
### character - desire
 - character_desire:: 
### character - lie
 - character_lie:: 
### character - fault belief
 - character_fault_belief:: 
### character - mistake
 - character_mistake:: 
### character - prejudice
 - character_prejudice:: 
### character - life lesson
 - character_life_lesson:: 
### character - dream life
 - character_dream_life:: 
### character - worst nightmare
 - character_worst_nightmare:: 
### character - fav memory
 - character_fav_memory:: 
### character - least fav memory
 - character_least_fav_memory:: 
### character - need
 - character_need:: 
### character - want
 - character_want:: 
### character - don't want
 - character_dont_want:: 
### character - current obstacle
 - character_current_obstacle:: 
### character - secret
 - character_secret:: 
### character - worldview
 - character_worldview:: 
### character - personal hero
 - character_personal_hero:: 
### character - internal conflict
 - character_internal_conflict:: 
### character - external conflict
 - character_external_conflict:: 
### character - what others think of them
 - character_what_others_think_of_them:: 
### character - self image
 - character_self_image:: 
### character - what they wish they could change
 - character_what_they_wish_they_could_change:: 
### character - what they wish they could have
 - character_what_they_wish_they_could_have:: 
### character - what get them fired up
 - character_what_gets_them_fired_up:: 
### character - worth taking risk
 - character_worth_taking_risk:: 
### character - things they take for granted
 - character_things_they_take_for_granted:: 
### character - inspiration
 - character_what_inspires_them:: 
### character - doubt
 - character_doubt:: 
### character - what makes them feel alive
 - character_what_makes_them_feel_alive:: 
### character - what makes them want to do better
 - character_what_makes_them_want_to_do_better:: 
### character - what do they want to be remembered for
 - character_what_do_they_want_to_be_remembered_for:: 
### character - how will the character change
 - character_how_will_the_character_change:: 
### character - power
 - character_power:: 
### character - immediate goal
 - character_immediate_goal:: 
### character - long term goal
 - character_long_term_goal:: 
### character - power level
 - character_power_level:: 
### character - first appearance
 - character_first_appearance:: 
### character - last appearance
 - character_last_appearance:: 
### character - mentor
 - character_mentor:: 
### character - inspired by
 - character_inspired_by:: 
### character - influenced by
 - character_influenced_by:: 
### character - most important person
 - character_most_important_person:: 
### character - prized possession
 - character_prized_possession:: 


## Society
### character - race
- character_race:: 
### character - wealth
- character_wealth:: 
### character - population
- character_population:: 
### character - language
- character_language::
### character - education
- character_education:: 
### character - culture
- character_culture:: 
### character - dogma
- character_dogma::
### character - attitude 
- character_attitude::
### character - culture 
- character_culture::
### character - religion
- character_religion::
### character - favored deity
- character_favored_deity:: 
### character - worship 
- character_worship::
### character - ritual
- character_ritual::
### character - celebration calendar
- calendar:: 



## Activities

### character - main goal
- character_main_goal::
### character - goal
- character_goal::
### character - public agenda
- character_public_agenda::
### character - tactic
- character_tactic::
### character - activity
- character_activity::
### character - product
- character_product::
### character - industry
- character_industry:: 
### character - import
- character_import:: 
### character - export
- character_export:: 
### character - technology
- character_technology:: 
### character - trade
- character_trade::



## History
### character - created date
- character_created_date::
### character - extinction date
- character_extinction_date::
### character - origin
- character_origin::
### character - creation
- character_creation::
### character - creator
- character_creator::
### character - modifier
- character_modifier::
### character - destroyer
- character_destroyer:: 
### character - reputation
- character_reputation:: 
### character - event
- character_event::
### character - evolution
- character_evolution::
### character - lore
- character_lore::


## Related info
### character - calendar
- calendar::

### character - chapter
- chapter:: 

### character - creature
- creature::

### character - general
- general:: 

### character - inspiration
- inspiration::

### character - location
- location::

### character - object
- object::

### character - organization
- organization::

### character - people
- people::

### character - scene
- scene::

### character - system
- system::

