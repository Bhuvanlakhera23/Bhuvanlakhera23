# Bhuvan Lakhera

I develop learning-based locomotion systems for the Unitree Go2. I implemented a
staged pipeline spanning Isaac Lab environments, PPO training, policy evaluation,
export and controller integration, and have worked on experiments with the physical
robot. My focus is blind locomotion: using proprioception and motion history to
negotiate terrain without a height map supplied to the actor.

That systems work led me to a research question: **how can a policy acquire harder
movement skills without losing useful locomotion?** I investigate this with Deepan
Muthirayan in our technical report on experience allocation. My earlier CanSat work covered
electronics, embedded sensing and wireless communication within a team-built payload.

## Selected projects

- **[Go2 RL Locomotion](https://github.com/Bhuvanlakhera23/go2-rl-locomotion)** — the engineering pipeline, robot demonstrations and measured obstacle-learning results.
- **[Go2 Learns to Climb](https://github.com/Bhuvanlakhera23/go2-obstacle-learning-rl)** — our technical report on experience allocation and acquisition–retention trade-offs.
- **[Robot Policy Tools](https://github.com/Bhuvanlakhera23/robot-policy-tools)** — independently authored CPU software for policy I/O validation and offline signal analysis; MIT licensed.
- **[CanSat](https://github.com/Bhuvanlakhera23/Canister-Satellite-for-Atmospheric-Data-Acquisition)** — electronics, sensor acquisition and Zigbee telemetry in a team hardware project.

## Explore the work

| Interest | Start here |
|---|---|
| Research results and methodology | [Go2 obstacle-learning report and numerical tables](https://github.com/Bhuvanlakhera23/go2-obstacle-learning-rl) |
| Engineering demonstrations | [Go2 simulation and physical recording gallery](https://github.com/Bhuvanlakhera23/go2-rl-locomotion/blob/main/docs/media-gallery.md) |
| Inspectable robotics software | [Policy contracts and signal metrics](https://github.com/Bhuvanlakhera23/robot-policy-tools/tree/main/src/robot_policy_tools) · [tests](https://github.com/Bhuvanlakhera23/robot-policy-tools/tree/main/tests) · [synthetic example](https://github.com/Bhuvanlakhera23/robot-policy-tools/blob/main/examples/synthetic.py) · [passing CPU CI](https://github.com/Bhuvanlakhera23/robot-policy-tools/actions/runs/43023067171) |
| Research reproduction | [Public analysis scripts](https://github.com/Bhuvanlakhera23/go2-obstacle-learning-rl/tree/main/scripts) and [CPU reproduction guide](https://github.com/Bhuvanlakhera23/go2-obstacle-learning-rl/blob/main/docs/REPRODUCIBILITY.md) |
| Embedded hardware | [CanSat electronics, sensing and telemetry](https://github.com/Bhuvanlakhera23/Canister-Satellite-for-Atmospheric-Data-Acquisition) |

The public scripts reproduce numerical analysis and figures, rather than PPO
training. The complete high-obstacle controller and training implementation remain
private. Robot Policy Tools is a separate software project and was not used to generate
the original high-obstacle benchmark. Educational code candidates remain local
and are not listed here as released projects.

## Research interests

Robot learning · Legged locomotion · Reinforcement learning · Sim-to-real · Embodied autonomy

[LinkedIn](https://www.linkedin.com/in/bhuvanlakhera/)
