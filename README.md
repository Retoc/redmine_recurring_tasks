# weekly_scheduler

Plugin is designed to make periodically issues copies for dealing with repetitive tasks

# Installation

* Ruby 2.3+
* Redmine 3.3+
* Standart install plugin:

```
cd {REDMINE_ROOT}
git clone https://github.com/constXife/weekly_scheduler.git plugins/weekly_scheduler
bundle install
bundle exec rake redmine:plugins:migrate RAILS_ENV=production
```

# Run

To run copying issues task you should run rake task

```
cd {REDMINE_ROOT}
bundle exec rake weekly_scheduler:exec
```

And to do it periodically you may use cron or another external scheduler.

# License

[MIT](https://github.com/constxife/weekly_scheduler/blob/master/LICENSE)