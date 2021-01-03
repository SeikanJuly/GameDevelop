drop database if exists `quest_db`;
create database `quest_db`;
use `quest_db`;

create table `list`(
`quest_id` smallint,
`quest_name` varchar(256),
`step` smallint,
`quest_type` enum('maim', 'side', 'events')
);

create table `players_progress`(
`player_id` smallint,
`player_name` varchar(30),
`player_mainqstates` smallint,
`stap_states` smallint
);
