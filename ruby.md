# 目次
- [メソッドの定義](#メソッドの定義)

# Ruby
## メソッドの定義
### アクセス修飾子のインデント
- アクセス修飾子(private, protected)以下に定義したメソッドはインデントを下げる

  ```ruby
  # 良い例
  def public_method
    # do something...
  end

  private

    def private_method
      # do something...
    end

  protected

    def protedted_method
      # do something...
    end

  # 悪い例
  def public_method
    # do something...
  end

  private

  def private_method
    # do something...
  end

  protected

  def protedted_method
    # do something...
  end
  ```
