# ChessHacks Waterloo

A 36-hour hackathon focused on building AI models capable of playing chess at a grandmaster level.

**Event Dates:** November 14-16, 2025  
**Location:** Waterloo  
**Website:** [chesshacks.dev](https://chesshacks.dev)

## Overview

ChessHacks is an intensive hackathon where participants collaborate to develop AI chess engines capable of playing chess at a grandmaster level. The event's spirit is to push the boundaries of chess-playing AI using neural networks as the heart of your solution, fostering hands-on experience, experimentation, and friendly rivalry. Teams have 36 hours to build and train their chess AI models, with creativity encouraged in both model design and training approach.

## What Makes a Valid ChessHacks Engine?

ChessHacks engines must place a neural network at the core of move generation—creativity is welcomed, but the network must be truly essential for producing moves. Your project should:

- Use a neural network as a critical component (if you can remove the network and your engine still works, it doesn't qualify)
- Output only legal chess moves under standard chess rules
- Integrate the neural network deeply into decision-making, not just as a superficial add-on

Architectures are flexible: end-to-end networks, networks guiding search (e.g., MCTS), lightweight evaluation networks, or language models fine-tuned for move prediction are all valid. For more on possible approaches, see [official rules](https://github.com/ChessHacks/rules).

## Notable Allowed and Disallowed Approaches

- ✅ Original neural architectures are encouraged
- ❌ Pre-trained chess models (e.g., models already trained on chess data) are strictly forbidden—you must train your own network!
- ❌ Classical engines without a neural-network core (like Stockfish) are not allowed
- ✅ Public datasets & knowledge distillation from chess engines are OK for training data

Full event rules (with clarifications/examples) are at the [rules repository](https://github.com/ChessHacks/rules).

## Event Structure

### Train

Teams have 36 hours to build and train an AI chess model, focusing on strategies from opening moves to endgame tactics.

### Iterate

Participants test their models against previous iterations, monitoring improvements in rating, move quality, and response times.

### Compete

AI models compete in real-time matches against other teams, culminating in a tournament to determine the strongest model.

## Competition Tracks

ChessHacks features five distinct competition tracks, each recognizing excellence in different aspects of AI chess development:

1. **Queen's Crown** 👑

   - Awarded to the best overall model in a tournament-style competition

2. **Rook's Rampage** 🏰

   - Recognizes the model with the highest ELO rating in a king-of-the-hill format

3. **Bishop's Gambit** ♗

   - Given to the first model that defeats Waterloo's strongest chess player

4. **Knight's Edge** ♘

   - Honors the best-performing model under 10 MB, emphasizing efficiency

5. **Pawn's Rebellion** ♙
   - Awarded to the first model that surpasses the baseline model provided by the organizers

## Participation Details

### Eligibility

- Open to all participants
- Priority given to students and recent graduates

### Requirements

- **AI/ML Experience:** No prior experience required, though a basic understanding is beneficial
- **Chess Skills:** Proficiency in chess is not necessary; the focus is on AI development

### AI Model Guidelines

Participants must build and train their own models entirely within the hackathon window and adhere to the spirit set forth above. Creativity in design and training is rewarded, but fairness and originality are paramount. See the [official rules](https://github.com/ChessHacks/rules) for up-to-date details and clarifications.

## Sponsorship

ChessHacks is supported by sponsors who facilitate the event and provide opportunities for participants to connect beyond the hackathon.

## Learn More

For more details, including FAQs and updates, visit the official website: [chesshacks.dev](https://chesshacks.dev)

---

_Note: Details are subject to change as the event approaches._
