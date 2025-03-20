# @see https://github.com/Homebrew/homebrew-bundle

###
# Application dev dependencies.
#
# Install with:
#   `brew bundle install`
##

# Only install development tools in non CI mode
if ENV.fetch('CI', 'false') != 'true'
  brew 'direnv'
  brew 'pre-commit'

  brew 'awscli'
end

# pre-commit requirements
brew 'markdownlint-cli'
brew 'yamllint'

# Only install these tools in development
if ENV.fetch('CI', 'false') != 'true'
  # terraform dependencies
  brew 'tfenv'
end
brew 'tfsec'
brew 'tflint'
brew 'terraform-docs'

# python dependencies
brew 'pyenv'
