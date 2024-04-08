# Optimized Revenue: Airline Strategic Overbooking & Dynamic Pricing
## General Overview

The project is centered on establishing the most advantageous pricing and overbooking strategies for an airline's coach and first-class tickets. It aims to boost profit from ticket sales while managing the repercussions of overbooking. For the sake of customer relations, the airline prefers to restrict overbooking to coach seats. Ticket pricing, which varies and influences the independent demand for each class, plays a pivotal role in sales probability, with coach sales likelihood increasing when first-class is fully booked.

Utilizing dynamic programming, the project explores various overbooking scenarios and pricing strategies to pinpoint the one that yields the highest expected discounted profits, thus proposing an overbooking policy that strikes a balance between maximizing revenue and reducing overbooking-related financial risks. The analysis is thorough, taking into account fixed costs, fluctuating demands, and the dynamics between the two classes of service, all to inform the airline's strategic decisions effectively.
V(c,f,t) = 〖max〗_(p∈{p_c ,p_f }) (R(c,f,p)+δ⋅E[V(c’,f,t+1)])![image](https://github.com/lvisa/Optimized-Revenue-Strategic-Overbooking-Dynamic-Pricing/assets/134125131/38dd85b1-91d9-4f0d-a2ba-d767453ec69d)
