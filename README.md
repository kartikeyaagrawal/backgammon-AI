# Backgammon AI

## Output

The program outputs:

- The optimal move sequence.
- The number of move combinations considered by the AI.

## How It Works

- **Minimax Algorithm**: The AI evaluates possible moves and future board states using the minimax algorithm.
- **Alpha-Beta Pruning**: Reduces unnecessary calculations by pruning branches in the search tree that are unlikely to lead to better outcomes.
- **Move Pruning**: Prior to the minimax search, a pruning step is performed to reduce the number of moves based on heuristic evaluations.

## Customization

- **MAX_DEPTH**: Adjust the depth of the minimax tree by modifying the `MAX_DEPTH` variable in the script.
- **Evaluation Function**: Tweak the AI’s strategy by customizing the `eval_fn` function in `backgammon_ai.py`.

## Contributing

Contributions are welcome! If you have ideas for improvements or new features, feel free to fork the repo, make changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
