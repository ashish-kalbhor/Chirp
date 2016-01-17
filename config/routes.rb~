Rails.application.routes.draw do
  get 'sessions/new'

  root             'chirp#home'
  get 'help'    => 'chirp#help'
  get 'about'   => 'chirp#about'
  get 'signup'  => 'users#new'
  resources :users
end

