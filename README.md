# Awesome Ruby
[![ruby-rocks!](http://img.shields.io/badge/ruby-rocks!-blue.svg?style=flat)](https://github.com/markets/awesome-ruby)

A collection of awesome Ruby libraries, tools, frameworks and software :gem:

Inspired by [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks) and [ruby-bookmarks](https://github.com/dreikanter/ruby-bookmarks).

Contributions are always welcome! Thanks to all [contributors](https://github.com/markets/awesome-ruby/graphs/contributors), you're awesome! The idea is to build a categorized community-driven collection. 

* [Awesome Ruby](#awesome-ruby)
  * [Style Guide](#style-guide)
  * [Package Management](#package-management)
  * [Environment Management](#environment-management)
  * [Documentation](#documentation)
  * [Testing](#testing)
  * [Web Frameworks](#web-frameworks)
  * [Web Servers](#web-servers)
  * [Database Drivers](#database-drivers)
  * [ORM](#orm)
  * [HTTP](#http)
  * [API Builder](#api-builder)
  * [CLI](#cli)
  * [Authentication](#authentication)
  * [OAuth](#oauth)
  * [Authorization](#authorization)
  * [Queue](#queue)
  * [Scheduling](#scheduling)
  * [Template Engine](#template-engine)
  * [Assets](#assets)
  * [Markdown Processors](#markdown-processors)
  * [Search](#search)
  * [Internationalization](#internationalization)
  * [Geolocation](#geolocation)
  * [Caching](#caching)
  * [File Upload](#file-upload)
  * [Email](#email)
  * [Form Builder](#form-builder)
  * [Imagery](#imagery)
  * [Video](#video)
  * [WebSocket](#websocket)
  * [HTML Parsing](#html-parsing)
  * [Web Crawling](#web-crawling)
  * [Processes and Threads](#processes-and-threads)
  * [Concurrency](#concurrency)
  * [Core Extensions](#core-extensions)
  * [Error Handling and Monitoring](#error-handling-and-monitoring)
  * [Code Analysis and Metrics](#code-analysis-and-metrics)
  * [Debugging Tools](#debugging-tools)
  * [Profiler](#profiler)
  * [Third-party APIs](#third-party-apis)
  * [CMS](#cms)
  * [Admin Interface](#admin-interface)
  * [Static Site Generation](#static-site-generation)
  * [Forum Engine](#forum-engine)
  * [E-Commerce and Payments](#e-commerce-and-payments)
  * [Analytics](#analytics)
  * [DevOps Tools](#devops-tools)
  * [Git Tools](#git-tools)
  * [GUI](#gui)
  * [Game Development](#game-development)
  * [Robotics](#robotics)
  * [Misc](#misc)
  * [Resources](#resources)

## Style Guide

* [Ruby style guide](https://github.com/bbatsov/ruby-style-guide) - Community-driven Ruby coding style
* [Rails style guide](https://github.com/bbatsov/rails-style-guide) - Community-driven Rails best practices and style for Rails 3 and 4

## Package Management

* Gems
  * [RubyGems](https://rubygems.org) - Community's gem hosting service
  * [Bundler](http://bundler.io) - Manage your application's gem dependencies with less pain

* Packages and Applications
  * [Homebrew](https://github.com/Homebrew/homebrew) - The missing package manager for OS X
  * [Homebrew-cask](https://github.com/caskroom/homebrew-cask) - a CLI workflow for the administration of Mac applications distributed as binaries
  * [CocoaPods](https://github.com/CocoaPods/CocoaPods) - The Objective-C dependency manager

## Environment Management
* [rbenv](https://github.com/sstephenson/rbenv) — Use rbenv to pick a Ruby version for your application and guarantee that your development environment matches production
* [RVM](https://rvm.io) — RVM is a command-line tool which allows you to easily install, manage, and work with multiple ruby environments from interpreters to sets of gems
* [dotenv](https://github.com/bkeepers/dotenv)
* [chruby](https://github.com/postmodern/chruby) - Change your current Ruby. No shims, no crazy options or features, ~90 LOC
* [ruby-install](https://github.com/postmodern/ruby-install) - Installs Ruby, JRuby, Rubinius, MagLev or MRuby

## Documentation

* [RDoc](https://github.com/rdoc/rdoc) - RDoc produces HTML and command-line documentation for Ruby projects
* [YARD](http://yardoc.org) - YARD enables the user to generate consistent, usable documentation that can be exported to a number of formats very easily

## Testing

* [RSpec](https://github.com/rspec/rspec) - Behaviour Driven Development for Ruby
* [minitest](https://github.com/seattlerb/minitest) - minitest provides a complete suite of testing facilities supporting TDD, BDD, mocking, and benchmarking
* [Test::Unit](http://test-unit.github.io) - Test::Unit is a xUnit family unit testing framework for Ruby
* [Cucumber](https://github.com/cucumber/cucumber) - BDD that talks to domain experts first and code second
* [Capybara](http://jnicklas.github.io/capybara) - Acceptance test framework for web applications
* [Appraisal](https://github.com/thoughtbot/appraisal) - Appraisal integrates with bundler and rake to test your library against different versions of dependencies
* [factory_girl](https://github.com/thoughtbot/factory_girl) - A library for setting up Ruby objects as test data
* [shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers) - Provides Test::Unit- and RSpec-compatible one-liners that test common Rails functionality. These tests would otherwise be much longer, more complex, and error-prone.
* [vcr](https://github.com/vcr/vcr) - Record your test suite's HTTP interactions and replay them during future test runs for fast, deterministic, accurate tests

## Web Frameworks

* [Ruby on Rails](http://rubyonrails.org)
* [Sinatra](http://www.sinatrarb.com)
* [Padrino](http://www.padrinorb.com)
* [Lotus](http://lotusrb.org)
* [Camping](http://camping.io)
* [Cuba](http://cuba.is)

## Web Servers

* [Rack](http://rack.github.io) - A Ruby Webserver Interface
* [Unicorn](http://unicorn.bogomips.org) - Rack HTTP server for fast clients and Unix
* [Thin](http://code.macournoyer.com/thin) - Tiny, fast & funny HTTP server
* [Puma](https://github.com/puma/puma) - A modern, concurrent web server for Ruby

## Database Drivers

* [ruby-pg](https://bitbucket.org/ged/ruby-pg) - Ruby interface to PostgreSQL 8.3 and later
* [mysql2](https://github.com/brianmario/mysql2) - A modern, simple and very fast Mysql library for Ruby (binding to libmysql)
* [SQLite3](https://github.com/sparklemotion/sqlite3-ruby)
* [redis-rb](https://github.com/redis/redis-rb) - A Ruby client that tries to match Redis' API one-to-one, while still providing an idiomatic interface

## ORM

* [ActiveRecord](https://github.com/rails/rails/tree/master/activerecord)
* [Sequel](https://github.com/jeremyevans/sequel) - Sequel is a simple, flexible, and powerful SQL database access toolkit for Ruby
* [Mongoid](http://mongoid.org/en/mongoid/index.html) - An ODM (Object-Document-Mapper) framework for MongoDB in Ruby

## Http

* [RESTClient](https://github.com/rest-client/rest-client) - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions
* [httparty](https://github.com/jnunemaker/httparty)
* [Faraday](https://github.com/lostisland/faraday)
* [excon](https://github.com/excon/excon) - Usable, fast, simple Ruby HTTP 1.1. It works great as a general HTTP(s) client and is particularly well suited to usage in API clients.

## API Builder

* [Grape](http://intridea.github.io/grape) - An opinionated micro-framework for creating REST-like APIs in Ruby
* [Rails::API](https://github.com/rails-api/rails-api)
* [jbuilder](https://github.com/rails/jbuilder) - Create JSON structures via a Builder-style DSL
* [rabl](https://github.com/nesquena/rabl) - General ruby templating with json, bson, xml, plist and msgpack support
* [Pliny](https://github.com/interagent/pliny) - Opinionated template Sinatra app for writing excellent APIs in Ruby
* [Roar](https://github.com/apotonick/roar) - Resource-Oriented Architectures in Ruby

## CLI

* [Rake](https://github.com/jimweirich/rake) - A make-like build utility for Ruby
* [Thor](http://whatisthor.com) - A toolkit for building powerful command-line interfaces
* [Commander](https://github.com/visionmedia/commander) - The complete solution for Ruby command-line executables
* [Slop](https://github.com/leejarvis/slop) - Simple Lightweight Option Parsing

## Authentication

* [Devise](https://github.com/plataformatec/devise) - A flexible authentication solution for Rails based on Warden
* [Authlogic](https://github.com/binarylogic/authlogic)
* [OmniAuth](https://github.com/intridea/omniauth) - A library that standardizes multi-provider authentication utilizing Rack middleware
* [Sorcery](https://github.com/NoamB/sorcery)

## OAuth

* [OAuth2](https://github.com/intridea/oauth2) - A Ruby wrapper for the OAuth 2.0 protocol
* [Doorkeeper](https://github.com/doorkeeper-gem/doorkeeper) - An OAuth2 provider for Rails

## Authorization

* [CanCanCan](https://github.com/CanCanCommunity/cancancan)
* [Pundit](https://github.com/elabs/pundit) - Minimal authorization through OO design and pure Ruby classes

## Queue

* [Resque](https://github.com/resque/resque) — A Redis-backed Ruby library for creating background jobs
* [Sidekiq](http://sidekiq.org) — A full-featured background processing framework for Ruby. It aims to be simple to integrate with any modern Rails application and much higher performance than other existing solutions.
* [Sucker Punch](https://github.com/brandonhilkert/sucker_punch) — A single process background processing library using Celluloid. Aimed to be Sidekiq's little brother.
* [Delayed::Job](https://github.com/tobi/delayed_job) — Database backed asynchronous priority queue


## Scheduling

* [Whenever](https://github.com/javan/whenever) - A Ruby gem that provides a clear syntax for writing and deploying cron jobs
* [rufus-scheduler](https://github.com/jmettraux/rufus-scheduler) - Job scheduler for Ruby (at, cron, in and every jobs)
* [resque-scheduler](https://github.com/resque/resque-scheduler) - A light-weight job scheduling system built on top of Resque

## Template Engine

* [Tilt](https://github.com/rtomayko/tilt) - Generic interface to multiple Ruby template engines
* [Haml](https://github.com/haml/haml) - HTML Abstraction Markup Language
* [Slim](https://github.com/slim-template/slim)
* [Liquid](https://github.com/Shopify/liquid)
* [Curly](https://github.com/zendesk/curly)

## Assets

* [Sass](http://sass-lang.com) - Sass makes CSS fun again
* Management:
  * [Sprockets](https://github.com/sstephenson/sprockets) - Rack-based asset packaging system
  * [Rails Assets](https://rails-assets.org) - Bundler to Bower proxy

## Markdown Processors

* [kramdown](https://github.com/gettalong/kramdown) — Kramdown is yet-another-markdown-parser but fast, pure Ruby, using a strict syntax definition and supporting several common extensions
* [Redcarpet](https://github.com/vmg/redcarpet) — A fast, safe and extensible Markdown to (X)HTML parser
* [Maruku](https://github.com/bhollis/maruku) — A pure-Ruby Markdown-superset interpreter

## Search

* [Thinking Sphinx](https://github.com/pat/thinking-sphinx) - A library for connecting ActiveRecord to the Sphinx full-text search tool
* [elasticsearch-ruby](https://github.com/elasticsearch/elasticsearch-ruby)
* [Sunspot](https://github.com/sunspot/sunspot) - A Ruby library for expressive, powerful interaction with the Solr search engine
* [Searchkick](https://github.com/ankane/searchkick) - Searchkick learns what your users are looking for. As more people search, it gets smarter and the results get better. It’s friendly for developers - and magical for your users.
* [pg_search](https://github.com/Casecommons/pg_search) - Builds ActiveRecord named scopes that take advantage of PostgreSQL's full text search
* [has_scope](https://github.com/plataformatec/has_scope) - Has scope allows you to easily create controller filters based on your resources named scopes.

## Internationalization

* [i18n](https://github.com/svenfuchs/i18n) - Ruby Internationalization and localization solution
* [i18n-tasks](https://github.com/glebm/i18n-tasks) - Manage missing and unused translations with the awesome power of static analysis
* [twitter-cldr-rb](https://github.com/twitter/twitter-cldr-rb) - Ruby implementation of the ICU (International Components for Unicode) that uses the Common Locale Data Repository to format dates, plurals, and more

## Geolocation

* [Geocoder](https://github.com/alexreisner/geocoder)
* [Geokit](https://github.com/geokit/geokit)

## Caching

* [Dalli](https://github.com/mperham/dalli) - A high performance pure Ruby client for accessing memcached servers

## File Upload

* [CarrierWave](https://github.com/carrierwaveuploader/carrierwave) - Classier solution for file uploads for Rails, Sinatra and other Ruby web frameworks
* [PaperClip](https://github.com/thoughtbot/paperclip) - Easy file attachment management for ActiveRecord
* [DragonFly](https://github.com/markevans/dragonfly) - A Ruby gem for on-the-fly processing - suitable for image uploading in Rails, Sinatra and much more!

## Email

* [Mail](https://github.com/mikel/mail) - A Really Ruby Mail Library
* [Pony](https://github.com/benprew/pony)
* [Mailman](https://github.com/titanous/mailman) - An incoming mail processing microframework in Ruby
* [MailCatcher](http://mailcatcher.me) - Catches mail and serves it through a dream

## Form Builder

* [Simple Form](https://github.com/plataformatec/simple_form) - Rails forms made easy
* [Formtastic](https://github.com/justinfrench/formtastic) - A Rails form builder plugin with semantically rich and accessible markup

## Imagery

* [MiniMagick](https://github.com/minimagick/minimagick) - A ruby wrapper for ImageMagick or GraphicsMagick command line
* [RMagick](https://github.com/rmagick/rmagick) - RMagick is an interface between Ruby and ImageMagick

## Video

* [Streamio FFMPEG](https://github.com/streamio/streamio-ffmpeg) - Simple yet powerful wrapper around the ffmpeg command for reading metadata and transcoding movies

## WebSocket

* [Faye](http://faye.jcoglan.com/ruby.html) - A set of tools for simple publish-subscribe messaging between web clients. It ships with easy-to-use message routing servers for Node.js and Rack applications, and clients that can be used on the server and in the browser.

## HTML Parsing

* [Nokogiri](http://nokogiri.org) - An HTML, XML, SAX, and Reader parser with XPath and CSS selector support

## Web Crawling

* [MetaInspector](https://github.com/jaimeiniesta/metainspector) - Ruby gem for web scraping purposes. It scrapes a given URL, and returns you its title, meta description, meta keywords, an array with all the links, all the images in it, etc.

## Processes and Threads

* [Parallel](https://github.com/grosser/parallel)
* [posix-spawn](https://github.com/rtomayko/posix-spawn) - Fast Process::spawn for Rubys >= 1.8.7 based on the posix_spawn() system interfaces

## Concurrency

* [EventMachine](https://github.com/eventmachine/eventmachine) - An event-driven I/O and lightweight concurrency library for Ruby
* [Celluloid](http://celluloid.io) - Actor-based concurrent object framework for Ruby
* [Concurrent Ruby](https://github.com/ruby-concurrency/concurrent-ruby) -
  Modern concurrency tools including agents, futures, promises, thread pools, supervisors, and more. Inspired by Erlang, Clojure, Scala, Go, Java, JavaScript, and classic concurrency patterns.  

## Core Extensions

* [ActiveSupport](https://github.com/rails/rails/tree/master/activesupport)
* [Ruby Facets](https://github.com/rubyworks/facets) - The premiere collection of general purpose method extensions and standard additions for Ruby

## Error Handling and Monitoring

* [Exception Notification](https://github.com/smartinez87/exception_notification) - A set of notifiers for sending notifications when errors occur in a Rack/Rails application
* [Errbit](http://errbit.github.io/errbit) - The open source, self-hosted error catcher
* [Airbrake](https://github.com/airbrake/airbrake) - The official Airbrake library for Ruby on Rails (and other Rack based frameworks)
* [Better Errors](https://github.com/charliesome/better_errors) - Better error page for Rack apps

## Code Analysis and Metrics

* [SimpleCov](https://github.com/colszowka/simplecov) - Code coverage for Ruby 1.9+ with a powerful configuration library and automatic merging of coverage across test suites
* [Rubocop](https://github.com/bbatsov/rubocop)
* [rails_best_practices](https://github.com/railsbp/rails_best_practices) - A code metric tool for rails projects
* [Flay](https://github.com/seattlerb/flay) - Flay analyzes code for structural similarities. Differences in literal values, variable, class, method names, whitespace, programming style, braces vs do/end, etc are all ignored. Making this totally rad.
* [Flog](https://github.com/seattlerb/flog) - Flog reports the most tortured code in an easy to read pain report. The higher the score, the more pain the code is in.
* [Brakeman](https://github.com/presidentbeef/brakeman) - A static analysis security vulnerability scanner for Ruby on Rails applications.

## Debugging Tools

* [debugger](https://github.com/cldwalker/debugger)
* [Byebug](https://github.com/deivid-rodriguez/byebug) - A simple to use, feature rich debugger for Ruby 2

## Profiler

* [ruby-prof](https://github.com/ruby-prof/ruby-prof) - a code profiler for MRI rubies
* [rack-mini-profiler](https://github.com/MiniProfiler/rack-mini-profiler) - Profiler for your development and production Ruby rack apps
* [perftools.rb](https://github.com/tmm1/perftools.rb) - gperftools (formerly known as google-perftools) for Ruby code

## Third-party APIs

* [Octokit](http://octokit.github.io/octokit.rb) - Ruby toolkit for the GitHub API
* [fb_graph](https://github.com/nov/fb_graph) - A full-stack Facebook Graph API wrapper
* [twitter](https://github.com/sferik/twitter) - A Ruby interface to the Twitter API
  * [t](https://github.com/sferik/t) - A command-line power tool for Twitter
* [tweetstream](https://github.com/tweetstream/tweetstream) - A simple library for consuming Twitter's Streaming API
* [ruby-gmail](https://github.com/dcparker/ruby-gmail) - A Rubyesque interface to Gmail
* [instagram-ruby-gem](https://github.com/Instagram/instagram-ruby-gem) - The official gem for the Instagram REST and Search APIs
* [soundcloud-ruby](https://github.com/soundcloud/soundcloud-ruby) - Official SoundCloud API Wrapper for Ruby
* [linkedin](https://github.com/hexgnu/linkedin) - Provides an easy-to-use wrapper for LinkedIn's REST APIs
* [Yt](https://github.com/Fullscreen/yt) - An object-oriented Ruby client for YouTube API V3
* [youtube_it](https://github.com/kylejginavan/youtube_it) - An object-oriented Ruby wrapper for the YouTube GData API
* [ruby-trello](https://github.com/jeremytregunna/ruby-trello) - Implementation of the Trello API for Ruby
* [hipchat-rb](https://github.com/hipchat/hipchat-rb) - HipChat HTTP API Wrapper in Ruby with Capistrano hooks

## CMS
* [Alchemy CMS](http://alchemy-cms.com)
* [Refinery CMS](http://refinerycms.com)
* [Radiant](http://radiantcms.org)
* [LocomotiveCMS](http://www.locomotivecms.com)

## Admin Interface

* [ActiveAdmin](http://activeadmin.info) - a Ruby on Rails framework for creating elegant backends for website administration
* [RailsAdmin](https://github.com/sferik/rails_admin)
* [bhf](http://antpaw.github.io/bhf/)

## Static Site Generation

* [Jekyll](http://jekyllrb.com) - Transform your plain text into static websites and blogs
* [Middleman](http://middlemanapp.com) - A static site generator using all the shortcuts and tools in modern web development

## Forum Engine

* [Forem](https://github.com/radar/forem)

## E-Commerce and Payments

* [Active Merchant](https://github.com/Shopify/active_merchant) - A simple payment abstraction library extracted from Shopify
* [Spree](http://spreecommerce.com)
* [ROR Ecommerce](http://www.ror-e.com)
* [stripe-ruby](https://github.com/stripe/stripe-ruby) - Stripe Ruby bindings

## Analytics

* [Gabba](https://github.com/hybridgroup/gabba)
* [Ahoy](https://github.com/ankane/ahoy) - A solid foundation to track visits and events in Ruby, JavaScript, and native apps

## DevOps Tools

* [Capistrano](http://capistranorb.com) - A remote server automation and deployment tool written in Ruby
* [Backup](https://github.com/meskyanichi/backup) - Provides an elegant DSL in Ruby for performing backups on UNIX-like systems
* [Puppet](https://github.com/puppetlabs/puppet) - An automated administrative engine for your Linux, Unix, and Windows systems, performs administrative tasks (such as adding users, installing packages, and updating server configurations) based on a centralized specification
* [Vagrant](http://www.vagrantup.com) - Create and configure lightweight, reproducible, and portable development environments
* [Chef](https://github.com/opscode/chef) - A systems integration framework, built to bring the benefits of configuration management to your entire infrastructure

## Git Tools

* [hub](https://github.com/github/hub) - a command line tool that wraps Git in order to extend it with extra features and commands that make working with GitHub easier
* [Rugged](https://github.com/libgit2/rugged) - Ruby bindings to libgit2

## GUI

* [Shoes](http://shoesrb.com)
* [QtRuby](https://github.com/ryanmelt/qtbindings/) - [Qt4 binding for ruby](http://quickgit.kde.org/?p=qtruby.git)
* [RubyGnome2](http://ruby-gnome2.sourceforge.jp/)

## Game Development

* [Gosu](http://www.libgosu.org) - A 2D game development library for the Ruby and C++ programming languages

## Mobile Development

* [RubyMotion](http://www.rubymotion.com) - A revolutionary toolchain that lets you quickly develop and test native iOS and OS X applications for iPhone, iPad and Mac
* [Ruboto](http://ruboto.org) - A platform for developing full stand-alone apps for Android using the Ruby language and libraries

## Robotics

* [Artoo](http://artoo.io) - Next generation robotics framework with support for different platforms: Arduino, Leap Motion, Pebble, Raspberry Pi, etc.

## Misc

* [Betty](https://github.com/pickhardt/betty) - Friendly English-like interface for your command line. Don't remember a command? Ask Betty
* [Foreman](https://github.com/ddollar/foreman) - Manage Procfile-based applications
* [Prawn](https://github.com/prawnpdf/prawn) - Fast, Nimble PDF Writer for Ruby
* [Pry](https://github.com/pry/pry) - A powerful alternative to the standard IRB shell for Ruby
* [Guard](https://github.com/guard/guard) - A command line tool to easily handle events on file system modifications
* [play ►](https://github.com/play/play) - Your company's dj
* [Treetop](https://github.com/cjheath/treetop) - PEG (Parsing Expression Grammar) parser
* [Kaminari](https://github.com/amatsuda/kaminari) - A Scope & Engine based, clean, powerful, customizable and sophisticated paginator for modern web app frameworks and ORMs

## Resources

* [GitHub Explore](https://github.com/explore)
* [Ruby5](http://ruby5.envylabs.com) - The latest news in the Ruby and Rails community
* [The Ruby Toolbox](https://www.ruby-toolbox.com) - A comprehensive catalog of Ruby and Rails plug-ins, gems, tools and resources for Ruby developers with popularity ratings based on GitHub watchers and Gem downloads
* [RubyFlow](http://www.rubyflow.com) - Ruby Programming Community Link Blog
* [RubyDaily](http://rubydaily.org) - Community driven news
