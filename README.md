# AI Game Bot for SEPIA Game Framework

SEPIA (“Strategy Engine for Programming Intelligent Agents”), a  game  environment  written  by  other  CWRU  students  tailored  to  writing  AI players. It's is a real-time strategy (RTS) game in which the goal is to collect different types  of  resources  in  the  map.  Typical  resources  are  “Gold”  and  “Wood.”  Resources  are collected  using  units  called  “Peasants.”  Having  resources allows the  player to build other  buildings (Peasants can be used to build things) and produce more units. Some of these units are battle units that can be used to  fight the opponent. Games  generally end when one player has  no  more  units  left. 

## P2Agent - PathFinding
Implementation of an agent that can move around a given game map using the A* search algorithm

## P3Agent - Playing  against an Opponent
Implementation of the alpha-beta algorithm for playing two player games to solve  some  SEPIA scenarios. Uses heuristics to determine  good  node  orderings. 

## P4Agent - Automated  Resource Collection
Implementation of  a forward  state  space  planner using  the  A*  algorithm that finds minimum makespan plans to achieve a given goal. Here makespan is time taken by the action sequence when  executed.

## P5Agent - Enhanced Automated Resource Collection
Agent can parallelize Move, Harvest and Deposit actions heuristically to execute at the same  time  by  noticing their preconditions can be simultaneous satisfaction.  This is sort of behavior falls under Scheduling, a part of Automated Planning.
STRIPS- like  description  of  the  BuildPeasant  action also included

## P6Agent - Automated Tactical Battles
Implementation of Reinforcement Learning Agent to learn to fight a tactical battle situation.    

Worked on thie AI Project while collaborating with 2 other fellow mates as part of AI course
