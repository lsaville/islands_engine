# IslandsEngine

The game engine that forms the base of the project outlined in [Functional Web Development with Elixir, OTP, and Phoenix](https://pragprog.com/book/lhelph/functional-web-development-with-elixir-otp-and-phoenix)

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `islands_engine` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:islands_engine, "~> 0.1.0"}]
    end
    ```

  2. Ensure `islands_engine` is started before your application:

    ```elixir
    def application do
      [applications: [:islands_engine]]
    end
    ```

