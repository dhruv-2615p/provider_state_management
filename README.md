# test_provider_s_m

A new Flutter project.

- Select it is usefull to see only some specific changes in our provider, it say our build functino of widget that see this aspect of this thing/s if it changes then rebuild your self.

- It can be used inside build method of our widget.

- Read it should ideally be used in only inside void call back to communicate you to your provider.

- Watch allow us to watch any changes and listen to that changes that happen to our provider.

- If we are outside of build functino then use Provider.of<T> instead.

- Consumer allow us to obtain value from a provider when we don't have a BuildContext, that is desendent of said provider. so we can't use Provider.of

- When some change occure in provider then every time build will be rebuild but child won't.