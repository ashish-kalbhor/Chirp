Rails.application.routes.draw do
  root             'chirp#home'
  get 'help'    => 'chirp#help'
  get 'about'   => 'chirp#about'
  get 'signup'  => 'users#new'
  get    'login'   => 'sessions#new'
  post   'login'   => 'sessions#create'
  delete 'logout'  => 'sessions#destroy'

  resources :users
end

