# Riak Core library dependencies manager

The library should be used by Elixir projects that wish to use riak_core.
Building the newest version of `riak_core` that supports OTP21 requires certain overrides on dependent libraries, that are not possible to specify in `mix.exs` project configuration at the time.
This library works as a wrapper that takes care of building `riak_core` with the right overrides using rebar3.

