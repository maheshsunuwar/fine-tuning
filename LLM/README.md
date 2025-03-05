<div class='alert'>

### Fine Tuning LLM

</div>

Transforming a foundation LLM into a solution that meets an applications's nees requires a process called *`fine-tuning`*.

A secondaryh process called *`distillation`* generates a small (fewer parameters) version of the fine-tuned model.

Despite the relatively tiny number of training examples, standard fine-tuning is often computationally expensive. That's because standard fine-tuning involves updating the weight and bias of every parameter on each backpropagation iteration. Fortunately, a smarter process called `parameter-efficient` tuning can fine-tune an LLM by adjusting only a `subset of parameters` on each backpropagation iteration.

A fine-tuned model's predictions are usually better than the foundation LLM's predictions. However, a fine-tuned model contains the same number of parameters as the foundation LLM. So, *if a foundation LLM contains ten billion parameters, then the fine-tuned version will also contain ten billion parameters*.

This is where distillation comes in.

*`Distillation`* creates a smaller version of an LLM. THe distilled LLM generates predictions much faster and requires fewer computational and environmental resources than the full LLM. However, the distilled model's predictions are generally not quite as good as the original LLM's predictions.

*`Remember`*: LLMs with more parameters almost always generate better predictions than LLMs with fewer parameters.

Find more concepts here: https://developers.google.com/machine-learning/crash-course/llm/tuning


- [x] GPT2 - used twitter sentiment dataset
- [ ] BERT base uncased
