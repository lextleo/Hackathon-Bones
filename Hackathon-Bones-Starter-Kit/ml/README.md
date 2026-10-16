# Machine learning and experiments

Optional home for datasets, feature pipelines, model training, inference, and evaluation.

Suggested principles:

- Keep exploratory notebooks in `ml/notebooks/`; move reusable logic into importable modules.
- Record data source, licence, collection date, preprocessing, split strategy, and known bias.
- Separate training from inference and keep a reproducible evaluation command.
- Track meaningful baselines and error cases, not only one headline metric.
- Do not commit private, licensed, or large datasets without permission. Use `data/samples/` for small synthetic or shareable examples.
- Store heavyweight model files outside Git or use Git LFS / a model registry when appropriate.

For every model, note its purpose, inputs and units, output meaning, dependency/version, evaluation data, metric, limitations, and fallback behaviour.
