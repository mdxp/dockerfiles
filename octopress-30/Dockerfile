FROM mdxp/rvm-base

# Deps for gsl
RUN apt-get -y install libgsl0-dev

# Deps GEMS
RUN /bin/bash -l -c 'gem install rb-gsl therubyracer'

# Octopress GEM
RUN /bin/bash -l -c 'gem install octopress --pre'
