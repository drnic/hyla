# Asciidoctor::Hyla

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

    gem 'hyla'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install hyla

## Usage

gem build hyla.gemspec
sudo gem install hyla-0.1.0.gem

## Commands

More info about options and commands available can be find by running the `command line tool`

    hyla --help

Here are some examples of commands to create a new project, add artefacts (asciidoc files) watch resources and serve it using HTTP Server

### New project

- Blank project

    hyla new --blank ~/Temp/MyBlankProject

- Sample Project (training-exercises)

    hyla new --template_type training-exercises ~/Temp/MyTrainingProject