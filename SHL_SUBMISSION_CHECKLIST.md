# SHL submission checklist

## First public commit (baseline)

- [ ] Review the cleaned baseline notebook and actual aggregate report.
- [ ] Create `shl-grammar-scoring` under ShrutiSuman08; select Public.
- [ ] Upload the supplied files and reports folder, not the ZIP itself.
- [ ] Include `.gitignore` (show hidden files on Windows if needed).
- [ ] First commit: `Add Whisper and TF-IDF grammar scoring baseline`.
- [ ] Check the notebook, README, plot and training RMSE render correctly.
- [ ] Open the repository in an incognito browser to verify public access.
- [ ] Share the same code through a competition-associated Kaggle notebook or
      discussion, as required by the supplied public-code-sharing rule. Keep
      record-level outputs and derived files private; GitHub alone is insufficient.

Public files: authored code, in-notebook report, README, dependencies, license,
aggregate plots and metrics. Do not upload the competition WAVs, original CSVs,
transcripts, embeddings, model weights, row-level predictions or credentials.
Gitignore is not a privacy filter for browser uploads or notebook cell outputs.

## Each improvement

- [ ] Evaluate fairly on the same outer folds; tune inside training folds.
- [ ] Record method and actual training/held-out RMSE and Pearson.
- [ ] Commit validated changes with a descriptive message.
- [ ] Keep baseline comparison and limitations; do not claim pending results.
- [ ] Clear data-bearing outputs from any notebook uploaded publicly.

## Final submission

- [ ] Resolve 216 test IDs versus 204 sample IDs with the platform/organizers.
- [ ] Rerun the chosen final notebook privately and verify all cells complete.
- [ ] Include documented preprocessing, architecture, metrics and plots.
- [ ] Include the compulsory actual training RMSE for the final model.
- [ ] Record held-out RMSE/Pearson separately from training fit and leaderboard.
- [ ] Export a valid final output with correct IDs/order/schema and scores [0,5].
- [ ] Submit through Kaggle within the current daily limit.
- [ ] Record the actual submission name/identifier, score and time.
- [ ] Push the final clean notebook, report and tested dependency versions.
- [ ] Verify public repository access and correct Kaggle username.
- [ ] Complete the mandatory SHL form; upload/provide its requested output file.
- [ ] Keep form confirmation and the exact final output privately.

Form: https://shl1.fra1.qualtrics.com/jfe/form/SV_eWMhjeljEFzNqSy

No submission or leaderboard score is yet confirmed. The supplied baseline is
work in progress and is not the final submission notebook. The pasted rules
listed 100 submissions/day and up to two final submissions; verify the current
competition page's limit before submitting. The hiring email has no fixed
deadline but emphasizes time to first threshold achievement, approximately two
days of steady work, and understanding the approach for interview.
