# TransferStream

A test to create a batch that would download a specified file and transfer it
to a specified cloud service through it's API (i.e. download a csv from a
website and transfer it directly to your google drive)

**TODO: Add description**

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add transfer_stream to your list of dependencies in `mix.exs`:

        def deps do
          [{:transfer_stream, "~> 0.0.1"}]
        end

  2. Ensure transfer_stream is started before your application:

        def application do
          [applications: [:transfer_stream]]
        end

## Requirements

1. transfer_stream uses hound to get its web sessions and requres the use of selenium-server
  1. For ubuntu follow the guide bellow
	- [Ubuntu installation](www.installationpage.com/selenium/how-to-run-selenium-headless-firefox-in-ubuntu/)
