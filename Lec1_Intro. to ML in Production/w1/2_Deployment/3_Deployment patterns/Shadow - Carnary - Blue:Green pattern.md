## Shadow: human and ML run in parallel, ML system's output not used for any decisions during this phase
## Canary: roll out to small fraction of traffic initially, Monitor system and ramp up traffic gradually (not fixed schedule or ratio)
## Blue/Green pattern: Old/Blue version and New/Green version - Easy way to enable rollback

## Degrees of automation
 - Human only >> Shadow mode >> AI assistance (human in the loop) >> Partial automation (human in the loop) >> Full automation (AI dependece)

## Common deployment key ideas: Gradual ramp up with monitoring, Rollback